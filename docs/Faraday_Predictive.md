Contact: Geoff Walker <geoff.walker@faradaypredictive.com> and Will
Boulton <will.boulton@artesis.co.uk>

#### ongoing discussion

Actually for our purposes we're not wholly focused on how good their
data analysis is (though obviously if they manage to do a really great
job, that would be excellent) - our thoughts were that as long as
they've managed to design the system as a whole well, we could then
spend some time refining or rebuilding the predictive fault diagnosis
part, but what's really valuable for us would be a 'nice looking' user
interface (maybe as a web app, if they felt that was most appropriate?)
with capability to automatically provide reports, and a function to
schedule maintenance in the future, and update a log to keep track of
when known faults have happened; and the data stored logically in a
database that they could design (depending on if we only gave them CSVs
of the raw data). Perhaps one way to extend this into a more ambitious
plan would be to ask for them to additionally have a reasonable looking
phone app so that an engineer about to go to the site could get some
idea about what was wrong with the compressor they were looking at (or
make notes if they noticed something funny), whereas a manager on their
PC could have an overview of what was happening across the whole plant?

A different option, though of a similar nature, could be to ask for the
students to design a system such that their analysis of the data could
be easily extended (by us) e.g. by uploading Python scripts to a
repository and then getting results back in close to real time, with
graphical results displayed in a friendly format - that would also be
very valuable to us since and hopefully turn their task from just a data
analysis task into one of overall design of the entire system.

One other thing we had in mind (though I'd need to discuss first with
Geoff first) would be to provide a small bank of about 10 little DC
motors (in a suitcase-sized box and with power supply etc already set
up), and some sensors to go with them; if interfacing with that could
provide a similar level of technical challenge compared to interfacing
with the bike (in addition to using the sensor data to detect which
motors are showing anomalies and display the results), then that could
be very useful to us, and we'd be happy if the students wanted to test
these motors to destruction, in which case there would be far less need
for much insight into the mechanical systems as the problems introduced
should be completely obvious.

Predictive Maintenance of Industrial Equipment

Faraday Predictive is a small local technology company which uses sensor
data from electric motors to diagnose faults in rotating equipment (e.g.
fans, pumps, compressors), and provide advice to clients about
maintenance of their equipment. Useful advice contributes to the smooth
running of this industrial equipment, potentially saving customers
millions of pounds in some cases.

One of our customers operates in the gas industry. We have an expanding
dataset (still in use) of thousands of records from 72 identical gas
compressors, some of which have shown problems, that could be used to
train machine learning models, rather than relying on expert analysis of
each compressor. Your task is to deliver a system that can easily be
used both by site engineers to alert them to problems, and allow them to
provide feedback (alerting your system to when and where maintenance has
occurred), and site managers, to schedule maintenance based on your
models of machine health.

Potentially a project related to the company's work in condition
monitoring of rotating machinery, for example using machine learning for
failure prediction. However, this would have to be integrated into a
larger product concept.

Alternatively, perhaps adapt [The Headless
Bicycle](The_Headless_Bicycle "wikilink")?