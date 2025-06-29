Potential contact for 2020:

alex.healing@bt.com

On 31 Oct 2019: Just a note to let you know that due to time constraints
I will be unable to submit a brief this year I'm afraid.

On 7 Feb 2019, Alex says: Many thanks, I'll have a think and see what we
can suggest that is likely to fit the brief and be in touch I come up
with anything.

Previous contact: Daniel Garner, daniel.garner@bt.com

Daniel says:

We generate that brochure once a year during the summer, with the aim of
making it available to the universities that we are partnered with
during the start of term when students are choosing their projects. The
ideas come from all over the department, from tech's with problems they
want to learn about, to strategists with big new ideas.

I'm the point of contact between GES and universities across the East of
England, so I'm here to foster the relationships we have. My main role
here is technical so I can answer most queries, those I can't I'm able
to find someone who can.

Perhaps this year we should open a dialog when we begin compiling that
brochure, that way we can find some projects specifically tailored to
match our interests and yours.

## Analysis of suggestions for 2016 - (A) PLAUSIBLE

### Am I where I think I am?

#### Original suggestion

Today over1 billion Android smart phones rely on Google Location
Services to tell their users where they are and where they are going,
every day. Given the growing reliance on this information, how can users
be sure the location data they are relying on is accurate, reliable and
safe? How can they be certain that when they don’t want to disclose
their location, their device isn’t continuing to do so behind their
backs?

This project addresses the first concern by finding ways of trusting
location providers, so that users can place greater confidence in the
service they’re receiving. We suggest approaching the disclosure concern
by reviewing ways of locating a device, such as through connectivity,
sensors, and the immediate environment. Once we understand the options
for locating the device, we can implement ways of safeguarding
prevention of data collection. That way your private business meeting
really does stay private.

The outcomes of the project will be an improved understanding of how
location based services work, their strengths and weaknesses, and a tool
demonstrating the most significant aspects.

#### Alan comment:

Outcome of "improved understanding" is not within our scope, so we need
to focus on the "tool demonstrating aspects". This needs to be rephrased
so that "finding ways", or "reviewing ways" are specified as features of
that "tool"

#### Ian comment

Andy Rice could advise on this. Seems to me this requires a shim to
track information leaving the phone.

#### Andy comment

This is very vague. Is this about attacks where an attacker tries to
trick someone's phone in to thinking its somewhere where it isn't -
what's the threat model here? Or is it about reliability and detecting
failures in location estimates - like when you rely on a wifi
fingerprint for location and then the base station gets moved? I guess
you could build a tool to check whether the location estimates from the
device from different providers are consistent. To do this properly
you'd need your own database of cell fingerprints and wifi fingerprints
because its totally opaque in the android stack if you let google do it
for you.

Tracking information leaving the phone is a serious undertaking. There
have been projects such as taint tracking and secure multiexecution
looking at catching dynamic information flows and so detecting leaks of
private information but this is beyond the scope of a 1B group project.

Potentially one could do a project about location granularity reduction.
This would be an app that lets you share your location with others and
choose whether you share point, city, country level etc. You can build
this with an offline database from openstreetmap and then use some
crypto on the server to limit the dissemination of your location to the
provider etc.

### Automated network provisioning

#### Original suggestion

Teams of all sizes are embracing virtual environments for their servers
and processing needs, but often they still deploy the networking
elements of a system on physical network devices. The alternative is
that their administrators have to engage in a long and complex
configuration process to make a virtual network that fills their needs.

The aim of this project is to automate the creation of virtual networks,
with minimal user direction and configuration. The outcome should be
some software that can capture a user’s high-level requirements, inspect
the layout of virtual machines deployed on common hypervisors like
vSphere and OpenStack, and then automatically create and configure the
network infrastructure. The project would likely take a phased approach,
starting with simple networks and one hypervisor, but the potential
scope is huge.

#### Ian comment:

Once involved in a start-up to do some of this. I think the problem here
is going to be translating the problem - the guts of this would be a
graph algorithm and possibly not a hugely difficult one. I would worry
that second year students won't have enough exposure to real-world
networking infrastructure in order to understand requirements. The
effort would go into this rather than generating a body of software.

This could be averted if BT are happy to provide the underlying input
information and dependency constraints. Clarification required.

### Detecting power cuts from internet data

#### Original suggestion

Companies providing a service that relies on the UK’s power and network
infrastructure need to know when things go wrong as quickly as possible.
But with so much legacy infrastructure out in the wild, monitoring it
all becomes a complex and expensive task.

There may be an answer based on how traffic flows across the internet.
Can we inspect the data flowing across our network, and find a way to
detect a number of service deterioration events, or disconnection
events, and cluster them? If so, can we begin at a high level, for
instance clustering service disruption in order to localise it to a
particular failing device in the core of the BT network, before going
down to a low level, for instance clustering within a postcode?

The outcomes of this project will be a study of search algorithms that
allow us to detect power loss events, and a software tool that
implements it and maps the likely fault area. In order to make this
realistic, we expect to provide real anonymised data from the BT
network.

#### Alan comment:

Sounds good. We need to find out what the data is.

### What can my second factor be?

#### Original suggestion

Two factor authentication improves security of normal username and
password authentication by exploiting the “something I have, and
something I know” approach. The widest application of this is in the
banking sector, where a user authenticating online typically receives a
onetime code via SMS, which the website verifies. Other popular online
service providers, such as Google, Facebook and Dropbox, all offer
similar two-factor authentication systems too.

The aim of this project is to find new and unusual forms for the
“something I have” part. This must not have a negative impact on the
user experience, and not require a change of user behaviour. What about
using near field communication readers in mobile phones to read some
details from a credit card, or using session data in a user’s device to
see that they are using their home machine? Suh and Devadas wrote a
paper for the ACM entitled “Physical Unclonable Functions for Device
Authentication and Secret Key Generation”, in which they set out the
properties and examples of good unclonable functions. The paper may
serve as a good starting point for this project.

The outcomes of this project will be an evaluation of a range of novel
second factors, including an implementation of each. Each will need a
thorough analysis, so that we can understand how easy and secure each
option is. It should round up with a recommendation of the best of the
bunch.

#### Alan comment:

How close is this to the Pico project, or other security group work?
Should check with them. "evaluation of a range" of options is not an
approach we have recommended to group projects in the past, but could
conceivably be done.

#### Ian comment:

Agree. Is this a study or an implementation. One could take one factor
and feed it in. Talk to John Daugman???

### Auditing smart phone permissions

#### Original suggestion

Most users have dozens of free apps installed on their smart phones, and
many users don’t check what permissions are requested as they install
them. As businesses begin to champion bring-your-own-device schemes in
the workplace, understanding the vulnerabilities of these unknown
devices will be of paramount importance to system administrators.

The outcome of this project will be a smart phone app, which users can
install on their devices, and will give them informative output about
what applications have what permissions granted to them. In addition it
should highlight anything consider a specific threat, or any
applications with permissions that don’t align with its overt purpose.

#### Alan comment:

Ask advice from ARB - perhaps add the root-kit functionality to here?

#### Ian comment:

(or Andrew Rice, but yes)

#### Andy comment

This would be an app like this one I guess:
<https://play.google.com/store/apps/details?id=com.fsecure.app.permissions.privacy>

I don't know how you would identify applications with permissions that
don't align with their overt purpose.

You could however extend this idea a bit to have options like 'give me a
notification whenever an app which can cost me money is running'

## New suggestions for 2016 - (B) UNLIKELY

### IMSI Grabbing

#### Alan comment:

Sounds plausible - need an application idea that incorporates this
technique.

#### Ian comment:

I am not sure I understand this. If a mobile device is broadcasting the
IMIS every so often then I don't see how you can detect a grab. If the
mobile device is being tricked into broadcasting this then it is a bit
like the location project (you need a shim). If the mobile device is
responding to a legitimate request and someone is eavesdropping, you are
pretty much back in periodic broadcast cast.

#### Andy comment

I guess they are referring to this project:
<<https://github.com/SecUpwN/Android-IMSI-Catcher-Detector>>. I can
imagine a group being able to build this but how would be provide them
with any way of testing it - are we going to get some catcher hardware
for them to use? I don't know too much about IMSI catching or how
plausible it is with 3g or what countermeasures a phone can take

#### Original suggestion

An IMSI is an International mobile subscriber identity - every mobile
phone has one, and they are unique. Because mobile devices broadcast
their IMSI, threat actors have the opportunity to detect the presence of
a device. For individuals who are at risk from physical attack, such as
when carrying valuable goods or sensitive information between offices,
accidentally announcing their location may be unwise.

This project builds on the Open Source Android IMSI-Catcher Detector,
which implements ways of detecting IMSI grab attempts. We want to take
an extra step, and detect the attempt by device and radio behaviour,
rather than relying on whitelisting safe cell sites.

The outcomes of the project will be a tool that announces to the user
that their device has had an IMSI grab attempt directed at it. The ideal
solution will go one step further, by reporting on and implementing a
technique to prevent the threat actors from receiving the device’s IMSI.

### Has my mobile device been rooted?

#### Alan comment:

Not enough work for a team. Combine with one of the other projects, such
as permissions above?

#### Ian's comment:

Not sure about that. I am sure this is undecidable at some level.
Andy/Alastair consult?

#### Andy comment

This is a research question. Rootkit detection is hard and is an arms
race with rootkit manufacturers. Malware detection is easier. Quallcom
just announced this:
<https://www.qualcomm.com/products/snapdragon/security/smart-protect>
which captures events and then uses a classifier to identify malicious
apps. That's probably do-able for a group project (if you don't care
about the overhead of running the tracker).

#### Original suggestion

Rooting is the process of allowing users of smartphones, tablets and
other devices running the Android mobile operating system to attain
privileged control (known as root access) over various Android's
subsystems. For many people this is a good thing, because it enables
them to perform operations the platform normally prevents them from
doing. But what if someone else rooted the device without them knowing?

This project aims to find ways of detecting if the device has been
rooted without the knowledge of its user. Current techniques to do this
are weak, leaving ways to evade their detection.

The outcome of the project will report on and demonstrate an Android
application that implements novel methods of detecting the rooted state.
It will show how difficult it is to circumvent the detection, perhaps
backed up by evidence from the behaviour of real malware.

### Can you hack my IOT device?

#### Alan comment:

Where would the students get the devices from? Group coordination would
be tricky, but perhaps interesting. Danger that one student could find
the whole thing trivial, leaving others with nothing to do.

#### Ian comment:

Don't think there will be a problem finding devices. The real question
is whether a group can come up with a coherent harness that test's
devices without someone having to sit in front of protocol analysers.

#### Original suggestion

The concept of the internet of things (IOT) is the driving force that is
beginning to flood the market with small, often simple devices that
communicate over the internet. As the demand for these surges, how well
are designers taking care of security?

The aim of this project is to analyse popular IOT devices, such as smart
home sensors and smart watches, and see how they respond to well-known
network attacks such as man in the middle and data spoofing. Where there
are vulnerabilities, what data do they disclose? The outcomes of the
project should be an analysis of the vulnerabilities of these types of
devices and the consequences of their exploitation.

## New suggestions for 2016 - (C) INAPPROPRIATE

### Am I over sharing?

#### Ian comment:

Pandora's box. Best left to graduate students....

#### Alan comment:

How much is "over"? Could this be extended to consider people who are
invisible on the web, or don't have easily verified identities (perhaps
because of common name)? It's going to require a search index, and I
can't imagine any serious alternative to using Google API (or perhaps a
Google alternative?) Wouldn't want to encourage 1b students to create
indexing spiders.

#### Original suggestion

In recent years, many people have protested about how complex the
privacy settings of many widely used social media sites. Social media
sites like Facebook are not the only source of personal information that
is freely available online: there are professional sites like LinkedIn,
as well as less obvious sources such as electoral registers and local
planning authorities. Including privileged sources enriches the
available data even further, including things like credit checks.

The complexity arises from understanding and quantifying the reliability
of sources, and unifying different data sources. There should also be
consideration about how relevant the information is and which sources
are most trusted.

The aim of this project is to find a way to discover and present the
user with an assessment of how much personal data they have exposed
online. This method must be easy to use, and ideally, provide
recommendations about how to improve the situation if required.

### Sudo and network security

#### Alan comment:

Framed as a consultancy report - not enough design content.

#### Original suggestion

Understanding security is of crucial importance to business, for the
protection and availability of their IT infrastructure, and the
protection of intellectual property and customer data stored on it.

The best practice is to apply security in layers, but any security is
only as good as its weakest link, with perceived risk balanced against
the initial and ongoing cost of a solution. This project is to
understand what protection we can apply through skilful use of the Sudo
command set to a program or application, running on Linux and UNIX
devices hosted on a network operating Active directory.

The outcome of this project is to find, document and demonstrate ways to
enhance security using the Sudo command set. The main areas to address
are:

- Protection of the Sudoers file
- User account and role separation
- Protection against Sudo weaknesses that could lead to account
  compromise
- Applying penetration testing to demonstrate the strengths and
  weaknesses of the solution Further scope could include a cost, risk
  and benefits analysis, an analysis of usability and management
  overhead, and a comparison with other solutions.

### Anonymisation of big data sets

#### Alan comment:

Not appropriate for group project. Perhaps a technically minded student
at JBS?

#### Original suggestion

Big data and data security make up two of today’s hot topics. People
make use of these big data sets for research, system testing, freedom of
information disclosures, and even as resources in innovation
competitions. In order to safeguard the privacy of the people described
in this data, it must go through some anonymisation process. Narayanan
et al have written an insightful paper on the subject, titled “A
Precautionary Approach to Big Data Privacy”, that forms a good starting
point for this project. The Information Commissioners Office publishes a
Code of Practice about anonymisation, which sets out the reasons for and
standards expected of a solution.

This project aims to understand the anonymisation problem by
understanding the state of play in research and practice, and then
developing, or pointing at, robust but practical tools. These tools
should would work in both trusted, for instance audit use, and open, for
instance publicly released online, environments.

It should justify the value of data anonymity traded off against
retention of the statistical properties of the data. As an extra step,
the project could contrast research and system test value of anonymised
data with synthetically generated data sets.

### Hunting domain generation algorithms

#### Alan comment:

Looks more like a Part II project - explore a single data set, with not
much for a team to do.

#### Original suggestion

Malware deployed on the internet relies on contacting servers for its
command and control. There is a battle going on between the malware
designers and internet providers, where the designers open a new control
server, and the providers try to find it and block it as quickly as they
can to protect their customers.

The malware designer’s best weapon is the domain generation algorithm.
It is there to generate new domain names for the control servers
dynamically, so that the malware implants don’t have to contain a list
of control servers that they will use in the future, meaning internet
providers can’t pre-emptively block their URLs.

The aim of this project is to look into the DNS data flowing across the
BT network, and find ways to detect the activity of a domain generation
algorithm. When it identifies a generated domain, it should try to
cluster similar instances, and then try to classify it against known
malware. The ideal outcome is that we find new malware very quickly,
allowing us to block it or capture it for static analysis. In order to
make this project realistic, we expect to provide real anonymised data
from the BT network.

The outcome of the project should be software that can examine network
data, and carry out the clustering and classification. You could apply
many techniques, likely focussing around machine learning.

### Improving the performance of facial recognition algorithms

#### Alan comment:

Unlikely that 1B students would make progress on this. Could perhaps
focus on small dataset for candidate matches, in order to use a quick
and dirty algorithm rather than state of the art.

#### Original suggestion

Computer Vision forms a field of its own in research, and people have
made exciting breakthroughs in how well software can recognise and
identify individuals in an image. The process is still computationally
expensive, and when resource constrained, slow.

We would like to port the functionality to mobile devices, so that for
instance security personnel carrying cameras can have individuals around
them identified against known images in real time.

The outcome of this project would be a theoretical explanation and
demonstrable improvement in the time taken for identification. This
project would suit an advanced student with a background in computer
vision.

# Last year - 2014

Contacts: fraser.burton@bt.com

Projects proceeding:

- [Multi-touch Conference](Multi-touch_Conference "wikilink")
- [Money World](Money_World "wikilink")

### original suggestions

Project 1 : How important is visual feedback to the success of in air
gesture UIs ?

Catherine White

In air gesture control has been imagined for decades and was popularized
by the film Minority Report. In recent years, hardware such as Kinect
and Leap Motion have transformed the concept to technical reality.
However, no really pervasive in air gesture control UI has emerged. One
hypothesis for this lack of success is that lack of visual feedback make
such UIs difficult to control, requiring too much conscious effort. You
will investigate how providing visual feedback affects the ease of use
of an in air UI. You will consider the users awareness of himself and
his state of interaction with the system. You will develop a UI for the
purposes of running experiments (based on Leap Motion or Kinect
hardware) and run experiments to determine effortlessness of use. You
will choose whether to design a UI to be fully intuitive, or to develop
a UI which requires learning but is then very easy to use. The types of
visual feedback that you could consider providing to the user include:
wire frame models of the user interacting with the system; abstract
geometric representations (such as an bounding ellipsoid mapped to a
hand, or cursors mapped to the end of each finger); or variations of
colour, shade and shadow on the screen.

Project 2: Collaborative Multitouch Interfaces

Catherine White

10 point multitouch screens are now widely available, and continuous
surface touch interfaces are also technically possible. How can two or
more people make use of such an interface on a large screen or surface,
for collaborative activities? You can draw on examples from social
activities, games or the workplace and will think of a concept, develop
and implement it. Finally, you will need to design and run usability
tests of your idea to assess whether it has potential.

Project 3: [Novel interactive data visualisations and UI
demo](Novel_interactive_data_visualisations_and_UI_demo "wikilink")

Ben Azvine

BT’s networks are a source of huge quantities of time-varying data which
have many variables. A wealth of information can be extracted from such
data, but initial exploration of the dataset may be formidable,
particularly when the features of the dataset are initially completely
unknown. There are a few standard means of data visualisation including
trend graphs, bubble diagrams, network diagrams, pie charts,
geographical maps, sun ray diagrams, and radial views. This project asks
you to discover alternative Opensource visualisation techniques beyond
these methods and to build an interface using one of these for the
purpose of exploring a large, complex graph dataset visually in a way
that allows discovery of correlations and clusters in the dataset (such
as relatedness in a single or multiple category).

## 2013

Contacts: paul.reid@bt.com james.mistry@bt.com oliver.newbury@bt.com

Final project was: [Terabyte threat
analysis](Terabyte_threat_analysis "wikilink")

Original introduction via Calum Eadie