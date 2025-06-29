Contacts David Russell <david@thefusionworks.com> and Lindsay Manning
<Lindsay@thefusionworks.com>

1\) VR Motion Sickness

Motion sickness in VR is an imprecise science. There's a number of
factors that don't necessarily impact everyone in the same way. Possible
causes include;

Your brain trying to process movement whilst your body is still Images
being slightly out of sync with your actions e.g. turning my head and
imagery being more than 50 milliseconds behind Refresh rates on the LCD
screens inside the headsets Field of view (or lack of) within a headset

We've been caught out by it on a recent VR development and we consider
ourselves experienced VR developers. NASA have recently been caught out,
they did a VR app to allow users to explore the International Space
Station. There was a great deal of feedback about it causing motion
sickness. However some experiences do VR successfully with minimal
motion sickness. An example of this would be a recent game called Star
Wars Squadrons which is a mass market VR game. It contains many elements
that should cause motion sickness but don’t seem to. One of my
colleagues believes this is due to a device they've included in-game
which is a bobble head figure on your cockpit dashboard. The bobble head
responds to the direction you steer your aircraft which might help in
tricking the user’s brain.

There’s general guidelines e.g. don’t use VR if you have blocked sinuses
and take frequent breaks but these relate to the symptoms rather than
trying to stop it happening in the first place.

This is of particular interest to us. Whilst VR is linked to gaming,
it's not really our interest. We're doing more and more work with VR in
other fields e.g. visualising architectural designs and CAD models,
using VR within a medical or therapeutic for treating phobias or mental
health issues. May users will be experiencing Virtual Reality for the
first time and it's desirable to minimise motion sickness effects.

I'm not sure what the end deliverable for a student project might be. A
prototype VR application demonstrating best practice for example??

Feedback:

VR is usually popular with students, and we don’t have any VR projects
for next year. On the other hand, the VR headsets we have around the Lab
are rapidly ageing (Oculus Rifts, largely DK1), and in the COVID era,
it’s a lot less attractive to strap things on your face that are being
passed around students! I can imagine that students might create a
reference implementation of a VR experience that is predicted to reduce
motion sickness, although verifying this experimentally would make the
project more appropriate for a dissertation than a group design project.

2\) Web RTC

Feel free to ignore this bit… it’s more notes for me… I’m not sure how
to turn this into something that students could work on…

Web RTC is a subset of the HTML5 spec and enables real time
communications between browsers and devices. This might be audio/video
or a real time peer to peer messaging mechanism. Whilst it’s been in-use
for the last decade by major sites (e.g. Facebook) the Web RTC standards
have only recently been finalised. It’s free, it’s open source, it
enables experiences that weren’t possible and it’s not tied to any
proprietary software/company. It should, over time, begin to
revolutionise web development.

Web RTC development is hard. By it’s nature its asynchronous. This is
not the same kind of asynchronism as AJAX calls that many web apps
currently use; those are simple by comparison. Instead, its many calls
layered over each other with ever changing local and remote data.
Developing, testing and debugging is tricky… how might we improve on
this…

Feedback:

Would Web RTC be suitable for taking multiple MIDI streams from
different sources, time-stamping, and reassembling into a synchronised
band at the other end? I recently heard a fairly impressive session at
the Network Music Festival, where the band set up a four-bar riff, then
each player added improvisations that would be layered on the \*next\*
four bars. This could be set up as a blues jam, where you get on-screen
queues on what chord the song is up to, and you add MIDI notes that are
stored and forwarded for integration at the right time.

Previous involvement when company name was
[Altfusion](Altfusion "wikilink")