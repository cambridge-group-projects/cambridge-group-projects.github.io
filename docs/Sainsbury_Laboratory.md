Ioana Valea <ioana.valea@slcu.cam.ac.uk>

### Feedback in discussion

The machine learning methods that might be used to address your problem
are reliant on large training data sets to be effective, and it's not
clear that this could be done within the timeframe.

On the most optimistic timescale, could we imagine project structure
along the following lines?

`Week 1 - scoping and planning`
`Week 2-4 - build, program and test the image capture array and data annotation system`
`Week 5 - collect and label/annotate data`
`Week 6 - train machine learning system`
`Week 7 - integrate and demonstrate results`

Would 1 week of growing time be long enough to capture sufficient
variety of images for your research question? This timescale would also
require that your experts be available for data annotation / labelling
to be done in parallel with the data collection.

### Project proposal for Phenotyping

Internal project description Goal is to take pictures of growing
strawberries at different developmental stages to observe potential
phenotypical differences in Biosensor/Highlighter transformed plants.
The phenotypic traits include: • Leaf enrichment of 2-month-old plants,
i.e. transition from vegetative to reproductive stage o how and where
the next leaves emerge • Runnering vs. flowering o Does exogenous GA
affect the switch between them? o Does runnering exclude flowering? •
Flower development o Is flowering induced by blue light periods in the
morning hours?

• Fruit development

Materials: Plant material are 2-months old strawberries grown in a pot.
The time-lapse pictures must be taken in light and dark conditions over
a long period of time: o Runnering/Flowering 2-4 weeks of data
collection o Flowering/Fruiting 5-6 weeks of data collection

Method: Arduino platform with control of light (array) LED lights in a
growth chamber seem to work well. Lights and cameras (light and IR) must
be under Arduino control. Humidity and room temperature can be regulated
by the growth chamber. Cameras: three cameras per pot (light camera for
side growth and from above, one IR camera from the side) At any one time
at least two plants (WT vs. treatment/transformant) have to be able to
be observed. If possible two pots per treatment, total at 4 pots at any
one time is best. Each pot needs its own cameras and picture collection
due to the analysis afterwards. Data analysis: Design a package for
image-based tracking of strawberry development Jupyter/Python • Tracking
of runner growth • Tracking of fruit development • Mature flower
characterization Students should write code that could be eventually
shared via the PlantCV/Fiji platform or use available one. The program
must be able to identify and differentiate between runners, flowers,
leaves and fruit. Also identifying colours and their intensity is
important. Detecting size and changes in size is imperative. Being able
to quantify changes in size and structure is important. E.g. different
leaf shapes between treatments, different flower, fruit and runner sizes
as well. Taking pictures with object identifiable by bare eye is also an
important point.

Course of action

We will be firstly responsible for building a scaffold of how everything
should be positioned in the chamber, students will be responsible for
optimizing the positioning of cameras and sensors for optimal data
collection. They will then continue with the Arduino programming and
data analysis.

Project advertisement draft for students:

Are you interested in consulting for a team of international and
energetic synthetic biologists at Sainsbury Laboratory to contribute
developing a new phenotypic system for strawberries? We are currently
designing an Arduino-based imaging set up to track developmental stages
of woodland strawberry. We need you, a team of talented computer
scientists knowledgeable in Python to develop the basic platform for the
Arduino system and the subsequent image analysis preferably on PlantCV
and/or Fiji.