Andy Fawkes <andy.fawkes@bisimulations.com>

2018 idea:

Perhaps we could use a pretrained object recogniser to populate the
OpenGL model, along the lines of this project from last year? [Neural
Guide](Neural_Guide "wikilink")

The object in the real world is recognised and then perhaps from a
library of 3D models the real object is modelled in the virtual world.
Feels like there would be a number of challenges to overcome for the
students and it's a worthwhile project from our perspective.

Virtual World Generator

It is possible to make accurate 3D scans of indoor scenes using depth
cameras such as Google Tango or expensive LIDAR scanners. Although the
overall geometry is accurate, individual objects cannot be
distinguished.Your task is to use a simple SLAM algorithm to recover
overall room dimensions, but populate a navigable virtual world in
OpenGL using standard 3D library models of furniture and other objects
that have been recognised as belonging to relevant categories using
pre-trained deep neural net models such as NeuralTalk Model Zoo.

Original enquiry

Very much in the concept phase but the idea would be to use AI to
recognise objects in the real world and then place them in a virtual
world. One of the use cases would be for planning missions for say blue
light services/military. A drone would be sent into an area and scan the
scene, not only collecting the visuals but automatic recognition of say
doors, windows, fauna and flora etc which could then be used to populate
a simulation (eg. in OpenGL). This is a real issue as it's easy enough
to visualise a scene through cameras, LIDAR etc. but much more difficult
to categorise objects in the scene for use in the simulation were
interaction with objects is important.

We were funded by Dstl to look at this problem a year or so ago. It's
not just for use in simulation, drones need to understand their
environment better, so they don't bump into a window thinking it is a
gap. We worked with UCL and a few others using LIDAR data but we ran out
of time. Not sure if we still have the data but this would be an
alternative approach, perhaps using the cloud to do the AI processing. I
am thinking keep it simple, a camera senses a scene, the AI recognises a
door (for example) and populates/tags the virtual 3D world of the same
scene with the door.

2017 advertised:

[Simulation and Warning for
Cyclists](Simulation_and_Warning_for_Cyclists "wikilink")

My suggestion:

Too many cyclists in London and Cambridge are injured or killed by
collisions with trucks and buses. We have data that could help. All
Cambridge buses have real time GPS tracking, and cyclists often wear GPS
devices like the Pebble smart watch. We propose an online training
simulator, accessed from screens but based on real data, to help drivers
and cyclists learn to avoid such accidents. The real time data and
decisions can even be fed back to cyclists out on the streets, with
coded buzzes on their wrist helping plan routes and avoid danger ahead.
With real-time data throughout, it should be possible to coordinate the
simulator with real actions.

Based on idea:

Exploiting Wearables in the Virtual and Real Worlds

Our client wishes to explore the utility of using wearables to help
train and then guide/warn its employees working in hazardous
environments. As the first step your task is to create a testbed of a 3D
interactive world linked to a wearable (eg. a Pebble Watch). As the
human navigates this virtual world the wearable will vibrate to
guide/warn them. This is intended to help train them ahead of completing
the same task in the real world. Our client would also like to see this
same task carried out in the real world to help capture any training
benefits of using wearables in this way. An example of a task might be
navigating different complex routes around the Computer Laboratory
Campus. Following these demonstrations the client requires a report on
the benefits and challenges of using wearables in this way and
recommended next steps towards developing a robust fielded system.

Suggested, but not proceeding:

[Bus Buzzer](Bus_Buzzer "wikilink")

2017 idea:

Exploiting Wearables in the Virtual and Real Worlds

We would like a wearable (eg. a Pebble Watch) to provide feedback to a
human who is tasked with achieving goals within a virtual world to help
prepare and then guide the human carrying out the same task in the real
world. This might have a number of uses, for example guiding a human
when visibility is low in the real world, but we are open to other uses
both for training and for entertainment. We are also interested in such
a system being able to transmit data from the wearable to the virtual
world, eg. pressing a button on the wearable will trigger an activity in
the virtual world. This could be part of the task that the human has to
achieve in the real world and again will permit them to practice it in
the safety of the virtual world.

A Wearable-Virtual World Tie Up

Current wearable technology such as the Pebble Watch and Android Wear
provide feedback to users such as vibration in the real world. But what
might the value be linking such technology to the virtual world? The aim
of this project is to create a technology demonstrator that links a
virtual world/simulation to a wearable such as a Pebble Watch or at
least an emulator. Events that take place in the virtual world must
trigger physical feedback in the wearable such as vibration. The
feasibility of actions in the real world being transmitted into the
virtual world should also be investigated and ideally demonstrated (eg.
pressing a button on the wearable will trigger an activity in the
virtual world). The purpose of this demonstrator will not be prescribed
but we envisage that it might be used in training so that the user gets
feedback from their training that goes beyond what they would get with a
typical games controller, eg. a vibration signals that they have
achieved or failed a task and/or their performance is recorded on the
wearable.

Perhaps not for 2017:

Pictorial Turing Test

The traditional Turing Test is usually implemented as a text chat
session. Some trivial versions such as CAPTCHA test the ability to
translate pictures into text. But would it be possible for a machine to
pass a Turing Test using pictures alone, with no text at all?
“Questions” might take the form of maps, plans, charts or photographs,
and “Answers” could be interpretive drawings, perhaps in the style of
Cohen’s Aaron or Colton's Painting Fool. The only rule is no text or
numbers – imagine giving an iPad to someone who speaks a different
language, where you’d like them to believe that they are communicating
with a real person as they draw on the screen or capture images.

2016 project:

[Surprise the Singularity](Surprise_the_Singularity "wikilink")

earlier drafts ....

If a super-intelligent artificial intelligence takes over the world,
Cambridge is likely to be the first target. Unfortunately, we have
published important strategic information online, where the Singularity
can easily find it. For example, the Computer Lab layout is at
<https://www.cl.cam.ac.uk/research/dtg/openroommap/>, and the University
map at <https://wiki.cam.ac.uk/university-map/>. Your task is to confuse
the Singularity by creating distractor maps, navigated in way that a
disembodied mind might not realise are impossible, for example as
Moebius strips or non-Euclidean spaces. Don't show the whole map at
once, where the edges will spoil the illusion. But do include a
simulation of real activity - public transport synced with real-time
information from Cambridge buses, simulated self-driving cars, and of
course locative social media messages from the (simulated) people in the
panicking crowds.

Using the Computer Lab as a target might be good. We do have an open
format map of the building:

<https://www.cl.cam.ac.uk/research/dtg/openroommap/>

There is also a useful API that can be used for Cambridge-wide
applications based on an open map of the University:

<https://wiki.cam.ac.uk/university-map/Map_Annotation>

If we were looking at spread of information across Cambridge, it would
be possible to use the following system as a source, based on advertised
events in a particular location:

<http://talks.cam.ac.uk/document/XML%20feeds>

For example, we could model how long it takes for news of a human
extinction event to propagate from a seminar in this series, to the
various machine rooms that might house an AI:

<http://talks.cam.ac.uk/show/archive/52792>