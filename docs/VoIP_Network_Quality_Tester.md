Contact: John Palombo, [Metaswitch
Networks](Metaswitch_Networks "wikilink")
<John.Palombo@metaswitch.com>

VoIP and Video calls are very sensitive to latency, jitter and packet
loss in IP networks, but there aren’t many good end-user tools available
to determine how good a network is. This project creates a probe that
users can run on a standard end user device (e.g. desktop, tablet or
smart phone) that communicates with a remote server and provides an
indication of how good the network is and predicts the quality of calls
through it. Ease of use is essential – both to install/run and
presenting the results in a user friendly manner. Idea could be extended
for example to crowd-sourcing across many users in order to build a much
wider picture of the network, or to predict quality of a gaming
connection.

Feedback: Very timely. However, students may not have suitable signal
processing skills. Would this use separate audio hardware to inject and
capture controlled signals, or rely on intercept of system audio? Would
capture and analysis of video quality be an alternative?

Response: The project can actually be much simpler than you are thinking
and wouldn't need to sniff the network. You'd have two end point boxes,
each sending a stream of packets to the other at a fixed rate (like a
VoIP call, but you can think of it like a fast ping). The remote end
would then gather stats about the packet arrival times, specifically
packet delay (latency), the variation in packet delay (jitter) and lost
packets. That data alone would be very useful to characterise how good a
connection you have.

You are right that the next step to interpret how that affects a call
from knowledge of the codecs might be a bit tougher, but they could make
an empirical judgement by actually making a VoIP call over the same
network connection and judging the voice quality and correlating that
with the packet stats. In order to have a suitably poor network
connection to get some good data, they might need to get a bit creative
by connecting over a poor wifi or mobile network, but that should be
quite doable.