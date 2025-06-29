Contact: yuichi.abe@informetis.com

## 2021 Discussion

José Alcalá, Head of Data Science Team,

Boruo Xu (Bono), Head of Data Solutions Team,

A keystone in the transformation to Smart Grids is the synergy between
solar panels and batteries. This is a complex task that heavily depends
on the weather, energy tariff and human stochastic behaviour. Informetis
is an AI energy start up company that aims to empower the user in the
Digital Transformation of electricity data. We propose the
implementation of an Artificial Intelligent Agent capable of deploying
the best strategy for charging and discharging of domestic batteries.
This will aid the user to select the correct battery size to maximise
household energy bill savings. Thus a communication channel, such as a
native or web based app, needs to be opened with the user. The project
is suitable for a team of 6 people and it might be divided into three
modules: Machine Learning strategy for battery control, 2 people;
backend to support communication with the cloud, 2 people; and front-end
interface to show results to the users and, potentially, receive
feedback, 2 people. Informetis will provide historical household power
consumption and historical household solar generation for a set of
houses. We are hoping to use the tool that you develop to showcase to
stakeholders as a demonstration of smart energy technology.

Feedback:

I can see that implementing an algorithm to optimise battery selection
would be an important problem, but unfortunately our students are not
taught any topics relevant to battery technology, so would have to treat
the battery as a black box. My own estimate is that, if you had a
suitable training dataset, then implementing a machine learning
algorithm to solve this task on a black box basis might only take an
hour or two using Keras and TensorFlow (perhaps followed by a few more
hours playing with hyperparameters).

A p2p energy trading system sounds more appropriate. Here are a few
examples of previous projects that involved the implementation of market
or trading systems.

- [Trading Assistant](Trading_Assistant "wikilink")
- [Fly-past Finance](Fly-past_Finance "wikilink")
- [AI racing market](AI_racing_market "wikilink")
- [Scrobble Exchange: A massively multiplayer
  game](Scrobble_Exchange:_A_massively_multiplayer_game "wikilink")

Revised suggestion:

Home batteries are rapidly evolving and disrupting the market along with
PV panels. However, do you actually know whether you can benefit from
it? How much energy can you save? When do you reach the ROI? Finally, if
the number works for you, which one to buy? Your task is to create an
application that helps consumers to answer these questions. The user
will input through the interface different parameters for batteries such
as capacity, price, cycles, voltage, and so on. Your application will
use these user inputs and the historical data (i.e. energy consumption
and solar panel generation) to run a simulation of the best battery
control strategy and will yield how much energy will be saved. The
application may also recommend changes to user habits to improve
efficiency. This task entails very challenging Machine Learning problems
such as pattern usage modelling and forecasting, reinforcement learning
(for battery control policies) and optimization. Regarding the
interface, it has to be friendly and intuitive so the user can interact
often and give continual input to the system. In the future, p2p energy
trading can be also implemented.

Feedback:

\- You say “in the future p2p energy trading can be also implemented”.
Does this mean that the team should implement an API for future
integration with another system after the project ends, or is energy
trading part of the system requirement? (If it is part of the system
requirement, then how should the team interpret “in the future”?)

\- If the main purpose of the application is battery selection, why
would users be required to give "continual input"? Would users need to
replace new batteries very often, or does the continual input relate to
some other area of functionality?

\- If reinforcement learning is to be used, what system would be used to
test the control strategies? Would this be a battery simulation, or
actual batteries?

\- Where machine learning is to be applied for pattern usage modelling
and forecasting, are there existing data sets for training and test, or
would the students need to construct or acquire these?

\- If I understand correctly, the main output of the system is "which
one to buy”. Presumably this is dependent on retail price, availability,
and installer / supplier bundling. Are there existing suppliers whose
sites could be scraped for this data, or would the purchase decision be
based purely on technical performance and OEM pricing?

## 2020 Project

Client: José Alcalá <jose.alcala@informetis.com>

Proposal awaiting finalisation:

### Activity Analysis based on Smart Meter data

A rapidly aging population means assisted living is fast becoming a
major societal challenge. To support “Carers” assisting “Carees”, local
technology company Informetis provides smart sensors installed in the
fuse-box that determine if household appliances are ON/OFF. As routines
are typically closely related to appliance use, this proxies for
inhabitants' wellness. Your task is to create an app for carers to
support householders when they struggle to perform daily routines. You
may choose focus on detection of activities from the raw data, or the
interaction design challenges of choosing what should be communicated to
the carer and when.

## Past Years

2020 project: [Activity Analysis based on Smart Meter
data](Activity_Analysis_based_on_Smart_Meter_data "wikilink")

2019 suggestion: [Activity Recognition and Analysis based on Smart Meter
Data](Activity_Recognition_and_Analysis_based_on_Smart_Meter_Data "wikilink")

2018 project: [Energy Budget](Energy_Budget "wikilink")

2017 offer: [Energy with Social
Conscience](Energy_with_Social_Conscience "wikilink")

2017 suggestions:

Smart Homes and IoT

The Internet of Things (IoT) is now almost mainstream. There are a lot
of internet-enable devices such as smart sensors, connected appliances,
connected medical appliances and of course smart phones. These devices
are all constantly generating big data dependent on individual
lifestyles. In particular, smart homes are increasingly a growing topic
of interest amongst IoT technologies. Informetis, provides a cloud based
service which, through the use of a ‘single clamp’ sensor, provides
consumers with an ‘itemised view’ of their electricity bill. In other
words, the Informetis solution can transform ordinary and
‘non-connected’ appliances such as fridges, washing machines and
microwaves into ‘virtual’ smart appliances. Your task is to design and
implement an application which complements the itemised power
consumption data (that we will provide) with other 3rd party data such
as temperature, personal information and social demographics data to
make the combined user experience more useful and fun. Your ultimate
goal is to make the user far more engaged with their energy consumption
than they are today!

Alternative

When electrical appliances "waste" electricity, they convert it into
heat. The irony is that if you "save" energy by switching off a TV or
lightbulb, you then have to switch on a heater to stay warm! Since
heating accounts for most energy use in the UK, The only really
effective way to save energy at home is to turn the thermostat down. But
nobody likes to be cold. You have a business opportunity to compete with
an incredibly successful Internet of Things product - the "Nest"
intelligent thermostat. Instead of wasting energy on toasty houses, your
product will help customers stay warm for free by regulating your own
comfort. Monitor humidity, differential airspeed etc to maintain comfort
by putting on suitable clothes, eating hot food or even going to bed.