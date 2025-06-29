Contact: Mark Ogilvie <mark.ogilvie@jagex.com>

Considering possibility for 2019

## Suggestions for 2017

Project 1:

[Personal Reality](Personal_Reality "wikilink")

Project 2:

Multidimensional descriptive engine and visualisation system

Eric Lagel - Senior Producer (eric.lagel@jagex.com)

Joel Graham - Director of Analytics & Data Science
(joel.graham@jagex.com)

In games, as well as wider entertainment, there exist many different
systems to describe features of a product. From the user perspective
though, there is no consistency across vendors or platforms to provide a
common understanding of the products I may be interested in (e.g. is
this “MOBA” on PC the same as that “Action MMORPG” on Android?); it is
also not possible to describe what you want in anything other than a
narrow prescribed set of terms (e.g. how can I find a “laid-back” game
to play, looking across genres and platforms?).

The solution to that problem will require abstracting (is “laid-back”
similar to “calming”?) from multiple diverse datasets (e.g. parsing user
reviews? Ingesting App Store databases?), but this still leaves a
significant challenge in terms of making a powerful and intuitive system
that users can explore to find what they’re looking for. Does that mean
users prioritising match importance for chosen terms on a scale? Does it
mean a 3D space to navigate from the closest matches through less
similar games of potential interest? Can I …

Feedback:

We’ve certainly done related projects in the past. An effective method
for this kind of problem is to create word clusters using Latent
Semantic Analysis, or some other vector-based bag of words technique.
However, past experience is that the resulting functionality is rather
one-dimensional, and that our computer science students don’t have the
visual design imagination to create anything other than the first idea
you might think of (a word cloud in the projected vector space with font
size varied according to word frequency).

So if we were to offer something in this area this year, I’d like to
extend it a bit. Do you have a good training set of labelled user
reviews for your own products?

One thing that just occurred, looking at other design briefs under
development. I know that Runescape has players in other languages. Do
you have customer reviews in multiple languages?

------------------------------------------------------------------------

Thanks for the feedback Alan - replying here as there's not been a time
when Eric and I are both in the office, so I thought better to at least
get an initial response (which Eric can always correct as needed!).

From my side, I was expecting that one of the biggest challenges would
be engineering the ability to ingest and abstract from diverse datasets
in the wild. It's not something we have a training set for, and I think
Eric (who's closer to the understanding of end user needs) would be
imagining that the utility in the concept would require a far more
diverse set even for training than we would be able to provide.

That, and your two points about likely visual design constraints and
previous projects' similarities, make me suspect that this is not a
well-suited brief; I may be mis-interpreting though, and I'll wait to
see what Eric thinks - although my availability is limited, I will have
email access over the coming days.

Yours,

Joel.

------------------------------------------------------------------------

Although there would indeed be a degree of parsing and plumbing work
involved in ingesting a range of datasets, my guess is that this
technical work is likely to be very limited, by comparison to the amount
of time that the team would need to spend identifying candidate datasets
and negotiating access.

Generic tools for content-scraping of semi-structured data are more
challenging, but we already have a fairly sophisticated project in that
area for this year:
<https://wiki.cam.ac.uk/cl-design-projects/Retail_Startup_Automator>

I do think that visualisation of linguistic datasets is interesting -
and indeed, I have a couple of research projects going on in that area
at the moment. Perhaps if you had a specific example of a visualisation
(e.g. from another domain) that you would like to emulate, we could
consider that as a starting point?

------------------------------------------------------------------------

Original suggestion for project 1: Social positioning and influence in a
virtual space

Mark Ogilvie - Design Director (mark.ogilvie@jagex.com)

How we perceive ourselves socially is subject to many influences, and it
is a difficult subject to study objectively due to those influences.
Your goal is to use a virtual reality environment to study social
perception. The focus of the project should be to deliver a system
architecture that allows sociologists to track decisions and alter the
experience to challenge or support trends discovered in the data.

Within a virtual reality environment, we could allow subjects to create
their perceived self, using virtual, abstract objects of various shapes,
colours and sizes in an attempt to mimic the way our self-perception
changes under various influences. How are their creations influenced by
the objects available? How are the creations influenced by the other
creations in the area, be it anonymous or named? When tracked against
the creator’s personal details, what trends can be discovered? What
happens when subjects have the ability to “build” their perception of
others? Such a product could evolve to a mobile state, locking a
creation to a device and monitoring how a subject might change their
creation based on new locations and influences.

## Projects in 2016

- [Listening to a million
  voices](Listening_to_a_million_voices "wikilink")

<!-- -->

- [Dynamic Narrative](Dynamic_Narrative "wikilink")

## Further proposals

Sponsor: David Solari Email: david.solari@jagex.com

Full motion video adventure game engine and toolset:- This project is
about creating an engine and tool set which allows video footage to be
utilised for the production of adventure games. Film features would
include cutting, arranging, linking, freezing, zooming, and digital
items to be inserted in film, digital special effect insertion slow mo
and time lapse. Game features would include, two way dialog, path
selection, inventory, 360 camera control, nodal integration points and a
quick time interaction system. Control interface features would include
mouse and keyboard; mobile touch and VR gesture. A simple proof of
concept demonstrating the engine and tools would be required.

Strategy Card Game Creator (Sponsor: Mark Killey, email:
mark.killey@jagex.com)

Chronicle: RuneScape Legends is a new strategy card game based around an
innovative core mechanic and experimental card systems. While The
Strategy Card Game Creator would be the Super Mario Maker of the genre!

It would be a game in which someone can create their own collectable
card game, either single or multiplayer and share it with their friends.
A player needs to create their own ruleset, cards, card effects and
obviously a name for the game itself, which is then submitted to a
central server. Other people can then play the game, leave a rating and
feedback. The creator of the game will be able to see this feedback plus
other key metrics, such as how many people have played the game. Players
will also need to be identifiable so there would need to be some form of
account system. The key for success will be to provide an intuitive yet
sophisticated system that allows people to easily create or modify
rulesets and cards in which can sit innovative mechanics. On top of that
there will need to a be an effective system to ensure there is a
meritocracy where the best games are easy to find and play!

### More appropriate to MPhil student: Flame charts

(Sponsor: Philip Bielby, email: philip.bielby@jagex.com)

Google Chrome and Mozilla FireFox have some excellent profiling
frameworks that produce charts that show time on the X-axis, and what
has been taking up that time against that. This is extremely useful when
profiling games written in JavaScript. However, there is no readily
available complete solution to do this for a game not written for the
browser.

We would like to have a series of functions we can call from C++ to:

- Mark when a frame ends
- Record custom ‘method calls’ from game scripting languages
- Record other custom events

We would also like to record what is happening in our C++11 code without
having to manually instrument everything (perhaps using a custom LLVM
instrumentation pass or similar, although an idea that works on multiple
compiler frameworks (e.g. MSBuild/VS2015, llvm, gcc) might be preferable
(but tricky)). It might be wise to allow shorter running methods to be
filtered out if the data-set is too large, however (which I imagine
might require a buffering step).

This data could then be transferred to a web browser interface (perhaps
using the trace-viewer framework from Google Chrome:
<https://github.com/catapult-project/catapult/tree/master/tracing>),
preferably using WebSockets or similar to allow online gathering of data
in as simple a fashion as possible, so that you can simply press a
‘profile’ button in the game to start and a ‘stop’ button when you are
done, and have the view update with the profiling data that was
collected.

The display of data should

- Be as a ‘flame chart’, allowing the user to drill down to find exactly

what is happening and when

- Handle processing on different threads as separate charts, so

multithreaded behaviour can be seen clearly

- Highlight different types of event separately
- Show when frames end clearly

Possible extensions could involve adding events/instrumentation to track
memory usage/allocation, or ideas regarding profiling of GPU
utilisation.