Client: Steffen Oppel, [RSPB](RSPB "wikilink")
<Steffen.Oppel@rspb.org.uk>

The Yelkouan shearwater is a bird that migrates through the Bosphorus to
reach the Mediterranean, but nobody knows how many there are. Your
client has video of the migration as seen from different distances and
angles. Unfortunately computer vision algorithms can’t be trained
without ground truth count of how many birds are there. You will create
a CGI simulator of the flocking birds, including realistic atmosphere
and viewing conditions, to generate simulated video with known ground
truth bird numbers. The final stage is to train a machine learning
system using your simulation to automatically retrieve the number of
simulated birds, and then test it on a real migration video to yield the
number of real birds.