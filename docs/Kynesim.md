Client: Richard Watts <rrw@semiramis.org.uk>

2017:

[Auto-Archive](Auto-Archive "wikilink")

Earlier suggestion:

[Workable backups for small
offices](Workable_backups_for_small_offices "wikilink")

Based on:

Small offices, of 2-8 people, have networks of PCs, connected typically
by 100Mbit ethernet (1Gbit if you are lucky). They generate quite large
quantities of data - our office turns over perhaps 1Gb/person/month over
a dataset of maybe 8Tb/person.

We have a net connection of about 200Mbit down/ 20Mbit up.

We would like an off-site backup system; we're prepared to use USB hard
discs to physically carry data off site, but really important data
should be uplinked to somewhere in the cloud, like tarsnap or perhaps
Amazon S3 directly.

There are a few challenges here :

\- Locating what has changed is quite hard; remember, people are using
these machines constantly (and when they aren't, their daemons are); you
can't just scan the hard disc.

\- Deciding if it is important is difficult; yet another git clone of
the Linux kernel probably doesn't need (or want) to be backed up. My
"extra_special_ca_key.pem" probably does.

\- Transferring that data over the local network is nontrivial: 1Gbit
for 6 hours transfers 21.6Tbyte of data in total, at line rate.

\- Incremental off-site backups mean you need to index the data, both so
you can locate it for retrieval and so you know what is already stored
elsewhere

\- Budgeting the uplink for the most important data can also be tricky -
even USB3 hdds have fairly limited bandwidth.

\- .. and, of course, you need to somehow assign names to the data so it
can be specified for retrieval.

\- If you are of a paranoid bent (and even if you aren't) you will want
to encrypt the backups.

This project invites you to write a backup system suitable for a small
office environment. It should contain some kind of agent which runs on
the workstation PCs, and provide reliable on-site and off-site backup of
data which it considers to be important, according to some set of
criteria.

`It should intelligently schedule backups so as not to hog the local`

network, internet uplink, or attached media.

`You will likely want to implement some level of deduplication.`

`If you finish that off easily, you could look at providing encryption.`

`(b) Automatic location of "interesting" features in large datasets.`

Large compute engines can create an awful lot of data - from eg. traffic
logs, or load monitoring.

This data is commonly quite unstructured - XML files, syslogs,databases,
CSV files. This makes it quite time-consuming to write python scripts to
spot "anomalous" data patterns which might indicate resource starvation
or incoming attacks.

This project invites you to implement a set of data extractors which can
break apart common file formats.

It then invites you to build a set of classifiers which attempt to spot
"anomalous" areas of data.

`.. and then a set of visualisations with which you can present those areas`

to the user.

It is likely that you will want to do this by at the very least
heuristically labelling types of data (e.g. "time since the epoch"), and
then running statistical classifiers, or NNs over the data to locate
areas of uncertainty.

I believe I have a source of supply of these datasets (Ian Jackson has
some from his build farms that he can probably let loose on unsuspecting
IBs)