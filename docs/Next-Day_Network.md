# Next-Day Network

Client: Matt Millar, HomeServe EMEA.

When a boiler fails or a pipe bursts, customers expect an engineer at the door the next day. Behind that promise sit expensive decisions: how many engineers to employ versus subcontract, whether to base them at regional depots or send them home with their vans, whether to swap diesel vans for electric ones that need charging, and whether to train engineers across trades so that one visit can fix both a gas and a plumbing fault. Today these choices rest on experience and on incremental changes to a running business.

Your task is to build a simulator of a national home-repair network. It should generate realistic streams of household emergencies across the UK, dispatch a modelled workforce to them, and report next-day coverage, travel time, cost and emissions. Planners should be able to change the workforce mix, depot layout, fleet and skills, and see the effect on a map.

The hard part is making the simulation fast and credible enough to compare strategies. That means modelling demand that surges in cold snaps, road travel and EV range, and scheduling engineers efficiently.

HomeServe will provide anonymised job patterns and typical costs; open road and census data fill in the rest.

*This project is a strong candidate for machine learning, for example in forecasting demand and learning dispatch and scheduling policies. Ambitious teams could also explore quantum algorithms for the optimisation.*
