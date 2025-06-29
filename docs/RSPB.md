Contact: Steffen Oppel <Steffen.Oppel@rspb.org.uk>

Project confirmed for 2022:

[Migration Simulation](Migration_Simulation "wikilink")

The Yelkouan shearwater is a bird that migrates through the Bosphorus to
reach the Mediterranean, but nobody knows how many there are. Your
client has video of the migration as seen from different distances and
angles. Unfortunately computer vision algorithms can’t be trained
without ground truth count of how many birds are there. You will create
a CGI simulator of the flocking birds, including realistic atmosphere
and viewing conditions, to generate simulated video with known ground
truth bird numbers. The final stage is to train a machine learning
system using your simulation, and then test it on real migration video.

Project confirmed for 2021: [Computing for Bird
Colonies](Computing_for_Bird_Colonies "wikilink")

Original suggestion:

I would be interested to suggest a project as a client, that would allow
wildlife managers to count bird calls automatically from acoustic
recordings. Although there are several commercial packages available,
the ones we have tried so far (Raven, Songscope, SoundID) are
unsatisfactory (very high commission and omission errors) and all
require substantial up-front investment in defining the variability of
calls of the target species.

Ideally, we would like a simple-to-use software tool (R package or GUI)
that would allow users to upload recording files (in batches, as there
will generally be hundreds), click ‘run’, and then download a table of
the number of calls of different species in each recording file.

There has been huge progress in the automatic detection of bird
vocalisations in recent years (http://dcase.community/challenge2020/),
but most of these high-end algorithms are not accessible to wildlife
managers who generally do not have a programming background. So
essentially we would be asking students to translate existing algorithms
into an accessible platform that would work for wildlife managers in the
field. We have many hours of recording from seabird colonies that can be
used as training or test data.

Initial feedback:

Thanks very much for this suggestion, and I’m sure it would be an area
of interest to students.

I’m fairly familiar with this general field, having recently supervised
a PhD that set out to improve machine learning tools for bird call
identification by citizen scientists. Based on that experience, my
understanding is that the main problem holding the field back is lack of
segmented and labelled training data that has been collected in the same
environmental context where the system is to be applied (the question of
how a model trained with bird calls recorded in captivity can transfer
to natural environment is probably one for researchers).

I presume that your colony recordings haven’t been segmented, but it
might be interesting to train a model that aims to estimate colony size
from acoustic characteristics, rather than counting and classifying
individual calls. Do you have a range of recordings from colonies of
different sizes? If there are a mix of species in a given colony, are
estimates of the relative proportions available in your training data?

My PhD student ended up creating tools for field recording and
segmentation of bird calls with a mobile phone, and a game-based
interface to educate and practice identification (neither particularly
valuable in scientific terms, I’m afraid).

More details:

Thank you for the feedback - yes, we have recordings from colonies of
different sizes, and it is relatively straightforward to derive acoustic
'indices' for entire recordings (there are several R packages
available), but these indices don't often correlate very well with the
actual number of calls where we determined the number manually. Also,
the relationship between colony size and vocal activity will vary a lot
by species and is unlikely to be transferrable, so a more general tool
that simply enumerates the number of calls will have much broader
utility.

You are right that the lack of segmented training data is a big problem,
and one of the key issues of using any commercial software (which
requires a big up-front effort, and manufacturers will always blame poor
performance on the poor quality of your training data). However, my
limited understanding of the more sophisticated algorithms now employed
to automatically process acoustic recordings is that they can either
harness recordings for thousands of species from xeno-canto or the
Cornell Macauley library to identify species, or simply classify sounds
without supervision and then return counts of distinct categories of
calls. Basically, an unsupervised algorithm would first classify all the
sounds in a recording into more or less coherent groups, then return a
list of their abundance and some samples, which the end user can then
use to select the species of interest (and to discard background noise,
e.g. waves, cars, crickets, etc.).

We have many recordings from seabird colonies where there is mostly 1
species present, which should be an easier and more feasible data set to
work with than rainforest recordings with hundreds of simultaneously
vocalising species.

Further response:

Thanks for confirming the technical constraints. This is certainly an
interesting area, and a great opportunity for undergraduates to gain
some experience of working with such valuable data. One possible outcome
of these projects is that one or more members of the team, after gaining
some familiarity with the problem through a group project, may wish to
explore specific technical challenges in more detail either in a final
year dissertation, or even through graduate research.

I think your suggestion of starting with an unsupervised approach seems
very appropriate, and it would definitely be interesting to consider the
design of a tool-chain that makes experimental investigation of such
data sets more convenient. We try to scope the projects so that
different members of the team can contribute in different ways - for
example some could work on segmentation, some on development of
regression estimators, and some on interactive facilities for browsing,
labelling or data enhancement

I really like this demonstration (perhaps runs only on Chrome)
<https://experiments.withgoogle.com/ai/bird-sounds/view/>

As a demonstration of bioacoustics in creative applications I used to
load this full-page on a large touch screen and “play” the clustered
vocalisations like a musical instrument!