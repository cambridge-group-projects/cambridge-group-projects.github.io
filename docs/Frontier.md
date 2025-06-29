New Contact for 2025 is Head of Design Laurence Oldham, who plans to
raise with Oscar Cooper, Senior Director of Development

## 2021

### Confirmed: [Augmented Room Dressing for Zoom](Augmented_Room_Dressing_for_Zoom "wikilink")

Second project that was considered: Social Distance Modelling

Businesses would like to open up commercial spaces adapted for social
distancing measures. But what's the best way to guide people through
these spaces so they have the best chance of maintaining distance?
Design a simulation that can model customers as particles that freely
move around these public spaces keeping to an avoidance radius with each
other. Include directional markup (one way systems) that control the
flow of customers around the space. Track congestion metrics to evaluate
the safety of the building. With a complete simulation implement machine
learning techniques to generate the best directional markup for a given
space. Perhaps there are some good common techniques that any business
can learn from!

I wonder if the Feng Shui idea could be modified to provide some Covid
relief? Perhaps something that generates a dynamic Zoom background that
is based on a captured model of student’s actual room, but with
augmentations?

My Logitech webcam has an app with controls to pre-process camera input
before it goes to Zoom/Teams etc. However, perhaps it does this
on-camera, since it seems to be OS-independent.

## 2020

### Confirmed: [Robotic Warehouse Design Suite](Robotic_Warehouse_Design_Suite "wikilink")

Online shopping is taking over the world! A growth area in robotics at
the moment is the use of robots and AI in the efficient running of
warehouses and retail storage facilities. The team should produce a
virtual warehouse simulation and demonstrate how AI may be applied on
this training suite to control bots in their storage and retrieval of
randomised streams of orders for items to allow the suite to find
efficient methods of organising and driving a robotic warehouse area.
How AI is applied to the system, whether in terms of organisational
control, or manipulation, or both is up to the teams to decide.

### Locomotion System API middleware for games

In today’s game development world there are middleware solutions for
many of the problems facing games and simulation developers. One of the
areas currently dominated by bespoke programming is the area of
character locomotion through an environment. Focusing on 3d
applications, we would be asking a project team to create a general
library allowing developers to specify and create instances of
controllable objects, taking navigation directives, and within the
specified movement parameters of the object, navigating the world in
which it exists to reach its objective. This may involve traversing
uneven or barricaded terrain, and possibly even climbing walls or
traversing ceilings where necessary. The solution must have a means of
connecting with animation assets to control the movements of the object.
The system must support bipedal and other forms of controllable objects.

### Accessibility Assessor

Today, with smart phones being such powerful computational devices
equipped with cameras the opportunity to capture data from the world
around us has greatly increased. This project aims to produce a piece of
software which can be used on a smartphone to capture the 3d shape of an
interior environment in order to produce a simplified computer model.
This model may then be processed, perhaps by another device in order to
produce a node graphed plan of the floorspace. This plan could provide
useful views of the space in terms of accessibility and aiding planning
usage of existing space.

### Tidy Rescue Bot

We are seeing an ever increasing use of AI in real world applications
over time. One of the most useful potential applications is to enable
robots to do work in environments which could be hazardous to humans.
Such examples could be earthquakes, or the aftermath of tsunamis, or
even the problematic resolution of the Chernobyl nuclear disaster. We
would like the team to create a simplified 3d simulation of such
hazardous environments and produce a prototype software system to show
the possibilities of using AI to attempt to safely clear or access areas
following disasters. This may involve clearing rubble, or identifying
possible locations of victims. The bot should be demonstrable of working
in virtual environment showing it’s decisions and processes to make a
rescue attempt feasible.

### Feng Shui Online

Human’s are always going to be useful when tasked with subjective
problems. In Feng Shui Online you create a fun gamified physics sandbox
of your room and present it to other players online to tidy. You then
divide a quota of points to the players that made the best versions of
your newly organised room. Does it spark joy? Keep the experience
engaging so that players enjoy the process. With the data generated from
the players train an AI to see if it can generalise and produce
satisfying results.

## Project proposals for 2019:

with Olly Powell

[VR Avatar](VR_Avatar "wikilink")

#### Other suggestions not used this year

Character Locomotion Middleware

In today’s game development world there are middleware solutions for
many of the problems facing games and simulation developers. One of the
areas currently dominated by bespoke programming is the area of
character locomotion through an environment. Focusing on 3d
applications, we would be asking a project team to create a general
library allowing developers to specify and create instances of
controllable objects, taking navigation directives, and within the
specified movement parameters of the object, navigating the world in
which it exists to reach its objective. This may involve traversing
uneven or barricaded terrain, and possibly even climbing walls or
traversing ceilings where necessary. The solution must have a means of
connecting with animation assets to control the movements of the object.
The system must support bipedal and other forms of controllable objects.

Automatic accessibility assessor

Today, with smart phones being such powerful computational devices
equipped with cameras the opportunity to capture data from the world
around us has greatly increased. This project aims to produce a piece of
software which can be used on a smartphone to capture the 3d shape of an
interior environment in order to produce a simplified computer model.
This model may then be processed, perhaps by another device in order to
produce a node graphed plan of the floorspace. This plan could provide
useful views of the space in terms of accessibility and aiding planning
usage of existing space.

City generation

Create a program that can procedurally generate a city complete with a
road network and basic infrastructure. The goal is to describe methods
of generation that evaluate as well networked and functional cities
whether exotic or traditional. The system should be able to highlight an
estimated flow of people and traffic at various times of day depending
on the function of buildings, such as consumer or business locations,
and positioning of public services. Heat maps for access times for
ambulance and fire services for example should be available derived from
the road network.

## Project proposals for 2018:

Preferred? [Opposing Views](Opposing_Views "wikilink")

[VR AI Ping Pong Trainer](VR_AI_Ping_Pong_Trainer "wikilink")

Also with Eddy Aston in 2017 <eashton@frontier.co.uk>

-Simulation LOD-ing

Level-of-detail (LOD) optimisations have a long history in rendering. 3D
meshes and textures are simplified as objects move away from the camera,
avoiding wasteful computation where a user can no longer distinguish
finer details. There is increasing use of LOD-ing in other areas such as
animation and AI routines, allowong us to simulate large, active crowds
with high frequency details in the foreground. Can we use similar
techniques to simulate other systems which are otherwise too complex or
large to be fully computed? Perhaps a global weather simulation
interacting with person-sized physics objects, or a densely populated
world with interactions ranging from person-to-person up to
empire-to-empire. The challenge is in finding a generalised
representation of the simulation at small scales which has a stable,
consistent approximation at larger scales, allowing a user to zoom to
any point and see deterministic results. Can you include user input to
alter the simulation, and simulate that change at different scales and
over time? You may wish to do this on constrained hardware such as a
Raspberry Pi, where an otherwise simple simulation may be too complex
and so the gains of LOD-ing are necessary.

## Project proposals for 2017:

Creature Dash

In some video games over the years, and most notably of recent in No
Man's Sky, attempts have been made to make procedural alien life forms,
to give a sense of diversity and variety, yet avoiding the production
difficulties of manually creating and animating such a vast range of
potential life forms. A common thread in these products solutions has
been to come up with a malleable connected graph that can represent a
creature out of a small and finite number of given parameterised nodes.

The challenge is to build a platform which provides a number of
parameterised 'primitive parts' which may be connected together by users
in building block fashion to create automotive creatures with some kind
of walk, or propellant movement cycle. The users may also use other
provided simple building blocks to construct 'obstacle' courses to
commit their creatures to, to explore their success in navigating them,
and to see which creature finishes first. Innovations involving sensors,
planning, navigation and movement are welcome, but must extend the
modular parameterised system, rather than being specific to an
individual creature. The only rule is there must be no user interaction
with individual creatures during its progress on the course.

My version:

[VR Algorave DJ](VR_Algorave_DJ "wikilink")

Why can't a DJ be more like an orchestra conductor, remixing
instrumental sections and adding new expressive content, instead of
simply selecting from a library of prerecorded tracks? In the future
this will be possible, using a gesture controllers in virtual reality.
We can provide a Myo gesture control armband. Your task is to create a
VR space in which the DJs of the future will edit and configure
algorave-style music synthesis programs. You can use APIs for the Sonic
Pi music language from Cambridge's Sam Aaron as a back end to produce
professional-standard musical results.

VR DJ

Virtual Reality is becoming an increasingly popular medium for computing
applications, particularly in entertainment. There is currently a lot of
undiscovered potential in VR, especially related to it's use in
creativity and manipulation, rather than just in terms of 'experience'.
This project aims to explore the more tactile and immediate possible
uses for VR, to use a headset and application to create live, responsive
audio/visual entertainment, through the use of virtual controls
presented to the user, to allow them to mix audio, video and potentially
other media presented to an audience in real-time.

VR Minigame BuildSpace

VR has become a serious contender in the field of video games and
entertainment in the last few years. There is still limited applications
for it in the this area which allow users to build and share their own
games in a common virtual environment. Your task in this project will be
to build on the backs of some existing technologies to develop such a
space, allowing users to build operational games out of primitives,
assets and rules, and potentially even collaborating to do so.

and slightly more high level

Plan -> VR

This project is about interpreting 2d building plans given in a commonly
accepted format, and using this to produce a decorated and lit 3d
environment from the plan, allowing walls and faces to be set with
various materials, and so rendered as such from a palette of textures
and models. The environments should be navigable via a convincing VR
interface, potentially with the ability to manipulate and decorate them,
from within

## Projects in 2016:

[Equity Exchange](Equity_Exchange "wikilink")

## Projects in 2015:

- [Planet Builder](Planet_Builder "wikilink")

## Projects 2014:

- [Rent-A-Mob](Rent-A-Mob "wikilink")

<!-- -->

- [Set Builder](Set_Builder "wikilink")

<!-- -->

- [Multi Chat](Multi_Chat "wikilink")

## Projects in 2013:

Contact: Ben Nicholson bnicholson@frontier.co.uk

- [A platform for live online
  modding](A_platform_for_live_online_modding "wikilink")