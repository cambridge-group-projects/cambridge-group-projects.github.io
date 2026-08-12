Suggestions from 2023 round - may be starting point for a more
open-ended brief in future:

==============

1\. Client: Mark Gotham (mrhg2), "Four Score and More"
(https://fourscoreandmore.org) Title: "Playback time" Brief: "Playback
time" will offer users the opportunity to play along with short, simple
musical exercises on a MIDI keyboard or similar and receive automated
feedback on their timing and accuracy. The resource centres on basic
scale and melodies, along with musical fragments called "partimenti".
The app thus resembles the format of home practice assistance apps, but
will be free, open source, and centre on a set of musical materials that
have been developed over hundreds of years to teach both playing and
musical understanding simultaneously. The initial implementation for
this app was completed some time ago, building on top of the music21j
library (https://github.com/cuthbertLab/music21j) and including some
dynamic programming for handling user input. This project will need to
bring that initial implementation up to date and provide a more robust
UI.

==============

2\. Client: Mark Gotham (mrhg2) and Felipe Martins for "Four Score and
More" (https://fourscoreandmore.org) Title: "TiLiA: Timeline Annotator"
Brief: TiLiA (short for "Timeline Annotator") is a GUI-based tool for
aiding in the creation and use of graphic annotations on audio and video
files. It is primarily intended to aid musical analysis by showing
aspects such as the structure (e.g., the verse-chorus structure of a
song). Those graphics and annotations may be used to control playback
and enable filtered searches over a corpus of annotation resources
produced in this way. It is somewhat similar to the existing
AudioTimeliner (http://www.singanewsong.org/audiotimeliner/), although
already significantly more full-featured. The long-term goal is that it
will serve as the first step in creating an online platform where many
kinds of musical analyses can be easily shared and accessed. The current
state is an initial, offline implementation
(https://github.com/FelipeDefensor/TiLiA). The task for this project is
to build a web version of this on the "Four Score and More"
(https://fourscoreandmore.org) website. This may involve using elements
of the offline version, but will more likely mean building from scratch,
simply using that offline version for guidance.

==============