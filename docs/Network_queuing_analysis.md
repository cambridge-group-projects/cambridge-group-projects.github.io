Client: Pedro Estrela, [IMC (Netherlands)](IMC_(Netherlands) "wikilink")
(Pedro.estrela@imc.nl)

The Objective of this project is to measure network queuing in a
distributed network, by correlating packets between locations and
between different identifiers domains. Currently large financial
networks are monitored by means of network packet captures that are
pushed to central or distributed databases. These databases contain the
full lifetime of an opportunity, from receiving a public tick packet in
location A all the way to send a private order packet in a different
location B, including all the datacenters and all the
transformations/processing in between. Assuming that these captures are
accurately time synchronized, and there is auxiliary databases that
contain the exact or approximate mappings between identifiers domains,
it is then possible to accurately reconstruct the full lifetime of all
the packets that took part in an opportunity, and statistically compare
these to all other billions of packets, of all the other opportunities
that passed thought the same network equipment or trading applications.
Doing this correlation will enable to measure every single queuing
effect in every single step of every single packet, which will enable to
optimize and tune the current systems by removing the bottlenecks or
increase capacity at the choke points.

## feedback

This one looks quite interesting, with a solid technical component.
However, I had one question before proceeding - does your company have a
dataset suitable for analysis, and would you be prepared to share this
with the students on the team?

## response

We have an SQL database containing pre-decoded packets, captured in
multiple WAN and MAN locations, over several days. These timestamps are
all UTC PTP-synchronized
<http://tagus.inesc-id.pt/~pestrela/timip/Challenges_deploying_PTPv2_in_a_Global_Financial_company.pdf>

We are willing to share this dataset after some form of sanitization,
which we'll do before our first meeting.