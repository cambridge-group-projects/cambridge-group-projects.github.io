Client: Dominic Nancekievill, [G-Research](G-Research "wikilink")
<Dominic.Nancekievill@gresearch.co.uk>

In today’s world of high frequency trading, understanding the rapidly
changing quotes from a myriad of trading algorithms is a colossal data
processing problem. With tens of thousands of updates per second in a
single market, and limited space and power constraints, it is important
to be able to maximise throughput and resiliency with the hardware
available. Given a day of actual stock exchange data, your challenge is
to create a cluster to process and aggregate the data. Doing this with
real hardware is more fun - we can’t give you our data centre, but we
can supply you with a Raspberry Pi cluster.

Dynamically dealing with hardware failure, visualisation of the order
book, automated deployment and performance statistics are all areas that
you can explore.

We have supplied the Computer Lab with some additional notes indicating
where you can find sample data to work with and giving a little
background information. Please collect a copy of these notes (and some
Raspberry Pis and other kit) before getting started.

## Additional Notes

Firstly, you will need some sample market data to work with. The New
York Stock Exchange (NYSE) have a page describing their ARCA feed at
<http://www.nyxdata.com/page/1084>. At the bottom of the page are two
tabs: “Specifications” and “Sample Data”. Download everything from both,
then follow the instructions in “NYSE Arca Integrated Feed Sample Data
Directory Layout” to download the sample data.

The specifications provide all the information required to decode the
sample data, however they are written for an audience with a basic
understanding of how financial markets work. See “A Brief Introduction
to Financial Market Data” below for a few notes which might be worth
reading before getting started with NYSE’s spec.

Architecture-wise, it’s OK to write something on an ordinary PC to read
the sample file and distribute messages from it over a network. You can
then use the Pis to pick up the messages, display order books and
compute analytics. You do not necessarily have to write a decoder for
every message type in the specification – the lion’s share of the
messages will be trades and order book updates, these are the most
interesting things to visualise or compute analytics from but they only
use a small number of the message types.

### A Brief Introduction to Financial Market Data

The data in the sample file is an example of the market data an
electronic trading system would receive from the NYSE Arca exchange
during a trading day. Messages in the other direction (orders from the
electronic trading system to the market) are not included. Market data
messages generally serve one of three purposes:

1.  To update clients on the current state of the market, e.g. “the
    market is now open”, or “trading in Vodafone shares has been
    temporarily suspended”.
2.  To indicate when trades have occurred, e.g. “200 shares of Vodafone
    have been traded at a price of £2.22/share”.
3.  To describe the current state of the order book for each product
    traded on the market (more on order books below).

Most financial markets use some variant of a central limit order book.
The easiest way to explain this is by example:

Suppose I want to buy 1000 shares in Vodafone and I’m willing to pay up
to £2.21/share. I would send an order to the exchange saying as much. To
begin with the exchange doesn’t have a seller willing to sell to me so
it records my order on the order book for Vodafone and disseminates it
to all market participants via the market data. The order book has a bid
side (indicating potential buyers with how much they want to buy and
what price they’re willing to pay) and an ask side (indicating the same
for sellers). After my order the book looks like this:

`No Ask`
`--`
`Bid 1000 @ £2.22`

Now suppose someone is willing to sell 500 shares but they won’t take
less than £2.24. Their order doesn’t match mine because we disagree on
price, so their order goes onto the book too and it looks like this
(note that this isn’t a terribly good way to visualise an order book –
just one that works in email where any formatting I add may be mangled –
you can do better in the visualisations you’ll write for the Pis):

`Ask 500 @ £2.24`
`--`
`Bid 1000 @ £2.22`

Suppose another seller comes along with a better price, and another
buyer offers a worse price. The order book is sorted by price so it
might look like this (there have still been no trades):

`Ask 500 @ £2.24`
`Ask 800 @ £2.23 (New seller)`
`--`
`Bid 1000 @ £2.22`
`Bid 2500 @ £2.17 (New buyer)`

A bit of terminology before continuing: My order to buy 1000 @ £2.22 is
the highest bid price, which is referred to as “best bid”. Similarly
£2.23 is the lowest sell price, “best ask”. The best bid and ask prices
are collectively called “top of book” or “touch”. The difference between
the two touch prices is the “spread”, currently £0.01 in this example.
Prices can be in fractions of a penny (although they aren’t in my
example) – the minimum price increment is defined by the exchange on a
per-product basis.

Now imagine I decide that actually £2.23 is not such a bad price and I
really do want to buy Vodafone shares so I’m willing to pay it. I would
cancel my order for 1000 @ £2.22 and place a new order for 1000 @ £2.23.
The exchange will not normally disseminate a book where the best bid and
ask prices overlap (this is called a locked book if the prices are equal
or a crossed book if best bid > best ask – there are cases where it
happens but if you see it happening all day long then your decoder is
probably not working). Instead a trade happens. In this case what you
would see in the market data is something along the lines of the
following:

1.  My order for 1000 @ £2.22 being cancelled.
2.  The existing sell order for 800 @ £2.23 being executed – either one
    execution message which removes it from the book and simultaneously
    indicates that a trade of 800 shares at £2.23 has occurred, or
    alternatively some exchanges will send this as two messages, one to
    remove the 800 shares from the order book and the other to indicate
    the trade. You’ll have to check the ARCA specification to see which
    they do.
3.  The remaining 200 shares from my order being added (since my order
    has only been partially executed).

After these messages, the order book would look like this:

`Ask 500 @ £2.24`
`--`
`Bid 200 @ £2.23 (This is what’s left of my order)`
`Bid 2500 @ £2.17`

[Category:Raspberry Pi](Category:Raspberry_Pi "wikilink")