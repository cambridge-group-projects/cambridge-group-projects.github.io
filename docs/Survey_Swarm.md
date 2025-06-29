Client: Ashkan Tousimojarad, [ARM](ARM "wikilink")
<Ashkan.Tousimojarad@arm.com>

Autonomous robots often have to work with an incomplete model of the
world, and high-end devices such as the Dyson 360 Eye do their best to
construct accurate image maps of the rooms they work in. But if there
are many cheap robots, they can collaborate in a swarm to share
information. Your task is to create sensing and coordination
infrastructure so that a swarm of Pololu 3pi robots can use their
reflection sensors to work out the overall design of a black and white
floor pattern that they are moving over. To start with, they will have
to use dead reckoning to collect single data points for the shared
model. Eventually, they can reduce uncertainty (for example, if some
robots seem less precise than others) by delegating individual robots to
go and make further observations, navigating by the map of previous
attempts.