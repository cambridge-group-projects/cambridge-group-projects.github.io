Client: Richard Watts <richard@bigpayme.com>

Proposed projects for 2022:

- [International Treasury
  Service](International_Treasury_Service "wikilink")
- [Household Payment Pool](Household_Payment_Pool "wikilink")

Two suggestions:

\(a\) A treasury management system: BigPay operates in MY and SG and you
can move money between the two. Currently, we use an external service
provider to do this but obviously it would be more efficient to do it
ourselves. To do so, we would have to manage reserves of both currencies
(MYR and SGD), set an exchange rate, and execute and settle transfers.
It takes about a day to physically move money (via our partner banks)
between Malaysia and Singapore or between our currency brokers and us.
Your job is to design a software system capable of managing and
visualising these reserves. It should take a feed of the buy and sell
rates available to us from our partners at various distances (1d,7d,30d)
and export an API allowing users to give a target currency and amount
and receive a price (and then confirm the transfer). As far as possible,
the system should achieve optimal revenue. You will need to write a
simulator for exchange rates and for customer behaviour.

\(b\) Playing games with money is quite fun. As such, we'd like to
introduce a game in which housemates (or larger groups) can exchange
transactions. When you spend money, the transaction will be charged to
some random member(s) of the group - possibly split. The catch is that
you will never be charged more money than you would otherwise have spent
in a given period (tunable by either you or the group). Design suitable
rules and build a UI and transaction recording system that allows people
to play this game.