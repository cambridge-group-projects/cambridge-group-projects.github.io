Contact: Michael Gifford <Michael.Gifford@niab.com>

## Proposal for 2022

Simon Smart <Simon.Smart@niab.com>

Analysis of satellite imagery has become a crucial part of the business
of agriculture. One problem that needs solving at scale is a method to
automatically and accurately delineate the areas of crops, to enable the
imagery to be clipped for analysis.

Current offerings typically generate field boundaries which are not the
same as the planted area are a crop. They are also usually based on old
imagery. This can cause big discrepancies when used to forecast
production, especially in high value crops such as potatoes and
vegetables.

NIAB is seeking a service, ideally delivered via API, which can accept a
single geographic point and time period, and return the crop boundary in
a suitable format (e.g. GeoJSON). The image analysis system could make
use of temporal changes in the imagery, which provides valuable added
information. Classical image analysis should be able to solve this
problem although ML classifiers would also be of interest.

Since last year, we have found an alternative solution for acquiring the
data we need which combines SAR and optical data. The limiting step that
remains is to generate cropped area boundaries from a single point.
There are commercial services available, but they tend to limited in
geographic scope, and as Charles said they are the entire field rather
than the cropped area. Some that we have tested just returned
openstreetmap data. It is an active area of research - see e.g.
<https://gtr.ukri.org/projects?ref=106000>
<https://www.researchgate.net/publication/343802377_A_DEEP_LEARNING_ARCHITECTURE_FOR_BATCH-MODE_FULLY_AUTOMATED_FIELD_BOUNDARY_DETECTION>
although this is not our area of expertise.

The account would be to <https://www.sentinel-hub.com/> which provides
an API to easily acquire sentinel data for specific areas of interest.

Feedback:

Thanks for the link to the Hummingbird project.

I’m reluctant to set tasks for undergraduates where they are directly
competing with well-funded professional researchers. Do you think we
might be able to find an alternative way of framing the problem that did
not focus so much on the core algorithm, but a systems perspective that
incorporates a variety of technical elements in a novel way?

For example, the joint impact of Covid and Brexit seem likely to result
in major disruption of the field-to-table infrastructure that supports
arable farming in the East of England. Is there potential to use crop
imaging for crowd-sourced deployment of human resources in harvesting,
packing and distribution?

### Confirmed 2021 project: [Virtual Agronomist](Virtual_Agronomist "wikilink")

Background:

Using pesticides in an effective and responsible way is a critical step
in both reducing the quantities used and ensuring their impact on the
environment and the health of farmers and consumers is minimised.

NIAB holds one of the most comprehensive pesticide and plant protection
products databases in the UK. This database is used by farmers and
agronomists to search for products to use to protect their crops from
pests and diseases. There are many complex restrictions around the use
of pesticides including: timing of application and growth stage of the
crops, pest thresholds, maximum dose rates and number of applications,
to name a few.

NIAB would like to leverage this database to help advisors verify that
their pesticide recommendations are valid according to label
restrictions by building an ‘Agronomy engine’. The agronomy engine will
accept an input consisting of a list of pesticide applications and use
the information in the database to validate the input. Additionally, the
engine should be able to account for approved tank mixes (combinations
of pesticides in the same application) as recommended by the
manufacturer.

We would like the agronomy engine to report on the geographic locations
of the queries (at county level or equivalent) and the nature of the
queries in a consolidated way.

Feedback:

This looks like a nice application. I think I would include a pointer to
the the technical approach that might be involved - it looks as though
classical expert systems methods might be an appropriate way to encode
regulatory constraints, tank mixes and so on. Representing all the
relevant knowledge in a way that can be checked and modified by
agronomists, while offering clear advice to farmers, should be an
interesting challenge.

### 2020 projects

- [Automating Crop Canopy Data Collection for Crop
  Management](Automating_Crop_Canopy_Data_Collection_for_Crop_Management "wikilink")
- [Collecting Farm-sourced Data on Pest and Disease
  Pressure](Collecting_Farm-sourced_Data_on_Pest_and_Disease_Pressure "wikilink")

NIAB is the UK’s leading Crop Science research centre. Within our
portfolio of research we develop digital models to describe and predict
crop development. This has significant implications for agriculture and
more widely with regards availability of food.

We have a number of problems which I think would make interesting 1B
projects and I was wondering what the process and timings are for
submitting proposals?