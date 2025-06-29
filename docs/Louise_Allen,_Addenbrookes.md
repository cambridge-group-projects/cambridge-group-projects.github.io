Contact: "Allen, Louise" <louise.allen@addenbrookes.nhs.uk>

### 2016 agreed

[Eye-Tests on Demand](Eye-Tests_on_Demand "wikilink")

Louise notes: If the test is to be useful in clinical practice the
matching process is important a 50/50 chance of getting the correct
answer won't do!

### earlier suggestion

DIY eye-tests

Many people would benefit from a way to take calibrated eye tests at
home or in public places, rather than requiring special equipment and
professional supervision. Your task is to design a visual acuity test
that can be set up and administered using two screens - one four metres
away, and one in the user's hand (their own phone or tablet). The
distant screen could be anything capable of running a web browser, such
as a TV or public display, with authenticated coordination to the user’s
phone via a separate HTTP server. Once the test starts, users will need
to operate the local device without looking at it - using easy touch
controls, with instructions given by audio. You’ll need to investigate
the relevant standards and procedures to ensure that the result is
clinically valid.

### Original background

There are two projects, the simplest is a DIY visual acuity testing
system for hospitals / vision screening in the community

We see over 50,000 patients a year in the eye out patients dept at
Addenbrooke's and this sort of number is typical for a large teaching
hospital. Every patient has to have a test of visual acuity (threshold
of resolution, tested in a clinic setting using a Snellen or LogMAR
chart) before they have other tests and their consultation. This is the
bottleneck of the clinic because a nurse currently has to do every
visual acuity test and we only have 2 nurses to do this despite having 8
doctors seeing patients in clinic. Each test takes about 10 minute so
you can see how easy it is to fall behind.

I estimate that about 30% of patients would be able to assess their own
visual acuity if given an automated process, which is what I am looking
to develop. My idea is to have a touch screen tablet in front of the
patient which drives a second monitor 4 metres away. Optotype letters
would be shown on the distant screen, decreasing in size using a
staircase algorithm and the patient would match the letter to one of a
number displayed on the tablet screen in front of them until they make
50% errors. This would then give a threshold visual acuity which would
be recorded.

The optotype standards / sizes are well established. Auditory and visual
instructions would need to inform the patients what to do. We could use
accepted optotypes for kids - who would probably respond more positively
to this as a game than most of the elderly.

I imagine that it might be a little like the automated check outs in
supermarkets, gradually people will prefer to use the system so they get
through quicker!

The second project is to work on a visual acuity testing system for
pre-verbal children. I have previously developed a system called
KidzEyez which is now licenced which uses a webcam feed from the centre
of a display screen to monitor the responsive eye movements of an infant
to cartoon targets appearing in the periphery of the screen - which
informs us about the peripheral visual field of the infant. I have the
prototype at Addenbrooke's. Hazel Kay (who developed the established
Kays pictures visual acuity cards for children) and I would like to
develop a visual acuity test along the same lines - giving the infant
two targets of diminishing size to distinguish between and measuring
visual acuity as the smallest size of optotype to which the child sees
and looks towards. See
<https:www.tes.com/teaching-resource/kidzeyez-6380245> for info about
Kidzeyez.