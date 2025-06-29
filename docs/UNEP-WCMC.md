(UNEP World Conservation Monitoring Centre)

2020 projects:

- [Ecosystem Game](Ecosystem_Game "wikilink")
- [Support Sustainable Wildlife
  Trade](Support_Sustainable_Wildlife_Trade "wikilink")
- [Travelling Businesswoman
  Problem](Travelling_Businesswoman_Problem "wikilink")

Potential contacts for 2020:

Mike Harfoot <Mike.Harfoot@unep-wcmc.org> (computational modelling)

Ben Tregenna <ben.tregenna@unep-wcmc.org> (data infrastructure)

### Outlines for 2020

- Travelling Businesswoman Problem

We all need to reduce our Carbon Footprints and for many businesses,
flights are a major component of this. Design an online system to help
an SME (~100 staff) reduce its footprint by optimising planned travel on
an annual basis. Staff should be able to input potential business trips
to other institutions, conferences and meetings as well as contacts or
locations that it would be beneficial to visit if the opportunity arose.
The team should consider simple ways to collect this information and to
display advice or suggestions during the planning of a trip.

- Support Sustainable Wildlife Trade

UNEP-WCMC supports many developing countries in assessing the potential
levels for sustainable trade in wildlife for particular species. The
challenge for this team will be to use the data provided by existing
APIs to power a tool for countries to follow a methodology for producing
these reports for a given species/family. The tool must be easy to use
in target developing countries and allow the user to provide additional
local knowledge to supplement the global data provided by existing data
APIs and finally produce a summary report for future policy use.

- Ecosystem game/visualisation

UNEP-WCMC have been pioneering the development of an agent based model
of whole ecosystems, the Madingley model. This process based formulation
provides an engine that can be used in many ways. One of the key ways we
would like to use the model is to engage with the public and/or decision
makers. So, the challenge for the team working on this project will to
consider options for improving the way the model can be used, either
through a game interface or a visualisation interface for the model
engine. The principal aim will be to make the model more engaging and
exciting.

### Previous years:

[Eco-Location](Eco-Location "wikilink")

Wildlife and critical ecosystems around the world are protected by over
230,000 legally recognised zones called protected areas. These protected
areas range in size from local nature reserves such as at Coldhams
Common <https://protectedplanet.net/555561770> through to iconic
national parks like the Serengeti
<https://protectedplanet.net/555570276>.

Many user groups need access to this data. Whether they are global
extractives businesses looking to avoid environmentally sensitive areas
when planning concession sites, academic researchers in the field
wanting to know how a specific species interacts with the protected area
network, or tourists looking for a local beauty spot.

Whilst these areas can be visualised geospatially on
<https://protectedplanet.net>, there’s currently no quick way to
discover your current proximity to nearby protected areas. Furthermore,
the data is limited to technical information about the size and
classification of the site. There is no information about what’s inside
any given protected area. Is it barren scrubland or dense forrest? Is
there evidence of agriculture where there shouldn’t be, or has the area
been flooded? This extra level of information is extremely useful for
conservationists (including park managers) to track the health of a
protected area.

Your task is to build a mobile application that enables the user to
quickly orientate themselves with nearby protected areas, and serve
vital contextual data about those areas by accessing other services. You
should specifically include data from the European Space Agencies Global
Land Cover Layer to show the percentage of cover types within the
protected area (e.g. 40% Mosaic vegetation, 60% Mosaic grassland), and
you may include other information such as geolocated photos from Flickr,
or species from the IUCN red list of threatened species.

### Ideas for 2017:

#### Revised ideas

for "Finding Nature"

The European Space Agency publish a global land cover map. Students
could use this to show statistics on the type of land cover and
vegetation across a given protected area (e.g 40% Mosaic Grassland, 10%
bare areas). Its available via an API supplied by
<https://ramani.ujuizi.com/> (you can view the data here
<https://ramani.ujuizi.com/maps/index.html#>, and the classifications
here
<https://ramani.ujuizi.com/maps/layer_simS3seriesCoverGlobal_info.html>)
but also directly from the ESA
<http://due.esrin.esa.int/page_globcover.php> if they want to get into
some web GIS.

Using the ESA land cover map seems like a great idea. Mashing this up
with the protected areas database should indeed be about the right level
of complexity.

What might the functional goal be? To support activism or lobbying, or
perhaps eco-tourism, or citizen monitoring of development projects? For
students who have only a vague engagement with current affairs, it may
be necessary to give a fairly heavy hint about the benefits that could
be delivered by the novel technical capability.

#### Finding Nature

Wildlife and critical ecosystems around the world are protected by over
230,000 legally recognised zones called protected areas. These protected
areas range in size from local nature reserves such as at Coldhams
Common <https://protectedplanet.net/555561770> through to iconic
national parks like the Serengeti
<https://protectedplanet.net/555570276>.

Many user groups need access to this data. Whether they are global
extractives businesses looking to avoid environmentally sensitive areas
when planning concession sites, academic researchers in the field
wanting to know how a specific species interacts with the protected area
network, or tourists looking for a local beauty spot.

Whilst these areas can be visualised geospatially on
<https://protectedplanet.net>, there’s currently no quick way to
discover your current proximity to nearby protected areas.

Your task is to build a mobile application that enables the user to
quickly orientate themselves with nearby protected areas, and serve
vital contextual data about those areas by accessing other services such
as the IUCN list of threatened species <http://www.iucnredlist.org/> or
geolocated photographs of the area.

Consider what other information might be useful (and useable) in a
mobile context such as direction & distance to the boundary, or is
available through open data initiatives such as <https://openoil.net/>

Feedback:

A clear and straightforward application, but slightly below the level of
technical ambition that we typically aim for. It may well be possible to
think of an enhancement - for example, integrating with climate data to
assess effects of industrial pollution or infrastructure projects
resulting from prevailing windspeed.

#### Unearthing the scale of illegal wildlife trade facilitated by the web

The black market for illegal wildlife products is worth an estimated
\$19billion USD a year putting it on a par with drugs, human trafficking
and arms dealing in terms of scale.

Much of this trade is facilitated on-line either by traders knowingly
breaking the law, or innocent (if misguided) consumers buying items
without realising they are fuelling international crime and pushing many
species to the brink of extinction.

Your task is to analyse social media and online market places (such as
eBay and Etsy) to identify possible illegal wildlife trade in specific
items (such as ivory) or species in order to establish a credible,
defensible figure on the scale of the problem. How will you overcome
simple problems such as those people posting to raise awareness of
wildlife crime, and those facilitating it?

Once you have an efficient way of identifying the number of posts /
adverts relating to illegal wildlife crime within a given time period,
what other insights can you identify? Where are the biggest markets
(geographically and on-line) for example?

Feedback:

Would the CITES database be the best reference source for a list of
species that might be traded? It is easy enough to connect “ivory” with
“elephant”, but how might other species be connected with products that
are made from them? One possibility would be to use wordnet to establish
relationships between animals and sales descriptions, but I suspect it
does not have good coverage of exotic species. Another would be to scan
Wikipedia pages for endangered species, in order to find terms that
might appear in advertisements. Is this the kind of thing you had in
mind? This becomes rather more challenging, though we could perhaps
build on Microsoft Cognitive Services APIs.

### 2016 proposal

Strategic Selection

Some species are endangered, but not very genetically interesting, while
some very interesting species are (fortunately) rather common.
International legislation and conservation efforts should be prioritised
accordingly, but there is so much data to be taken into account that it
is hard to decide where to expend one’s efforts.The
<http://www.speciesplus.net/> application provides taxonomy,
legislation, distribution and trade information on controlled species
(which you can search filter and download), and the Trade Database,
<http://trade.cites.org/> gives historic trade data on all animals
traded and which are covered under the Convention on International Trade
of Endangered Species of Wild Flora and Fauna (CITES). Your task is to
create an evolutionary family tree that, rather than emphasising natural
selection, helps users navigate toward branches of the tree that need
strategic selection.

### early ideas

We work on data visualisations, on-line geospatial mapping and taxonomic
databases, generally focused on trying to communicate complex data to
non-specialists (policy & decision makers), so we believe in taking a
strong user centred development approach to our work.

In terms of taxonomic databases a good place to start would be our
<http://www.speciesplus.net/> application which lists taxonomy,
legislation, distribution and trade information on controlled species
(which you can search filter and download), and the Trade Database,
<http://trade.cites.org/> which gives historic trade data on all animals
traded and which are covered under the Convention on International Trade
of Endangered Species of Wild Flora and Fauna (CITES). Again, you can
filter and download this data freely.