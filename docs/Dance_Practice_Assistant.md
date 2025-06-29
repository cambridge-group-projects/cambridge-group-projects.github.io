Client: [Cambridge Consultants](Cambridge_Consultants "wikilink")

Contact: Rodrigo Queiro <rodrigo.queiro@cambridgeconsultants.com>

For learning swing dance routines such as the Shim Sham, dancers are
often taught individual stages of the routine without music, starting
from the teacher's count of "5, 6, 5 6 7 8!". This tends to lead to
unnecessary confusion later, when trying to match up the moves they've
learned to the music. Trying to practice to excerpts of the music is
currently tough, requiring teachers to hunt back and forth for the right
section.

I propose a system which takes a track and analyses it, perhaps with the
Echo Nest API, to identify the times of individual beats and split the
track into musical bars and phrases. This greatly aids the teacher in
splitting the track into distinct stages of the routine. Then, in the
class, the teacher can very easily request playback of a given stage,
allowing it to be practised individually to music. The application would
also allow the teacher to control the playback speed of the music, to
start of easy and build to full speed on later attempts - perhaps by
voice or a linked mobile phone app for convenience. At home, the student
can use the application to scrape a video off youtube and practise the
steps in a similar fashion. For added work, a Kinect-based or similar
system to track the dancer and work out what they were doing might be
interesting.

To follow up on what I said at the meeting, based on the success of
things like Swingify:
<http://musicmachinery.com/2010/05/21/the-swinger/>
<http://haveyouheard.it/a-swinging-hack-swingify/>

It seems that individual beat detection works very well, at least for a
subset of songs. The same API used for the underlying code:
<https://github.com/echonest/remix/blob/master/examples/swinger/swinger.py>
95 sloc!!! would probably be useful.

## feedback

Beat matching from audio is still a reasonably hard problem, but will
probably give acceptable results with relatively strict tempo dance
music of the kind used in lessons. Echo Nest seems like a good starting
point.

Andrew Knights also suggested a project that would require audio
tracking of music (his was more complex, potentially requiring
polyphonic pitch tracking as well). From past experience, although we
usually have a few musicians on the course, Computer Science seems to
attract slightly fewer musicians than most Cambridge degrees, so we may
not get enough interest to support two projects of this kind. Yours
seems more technically achievable, and may also benefit from the
Strictly Come Dancing audience (though this may not be large among
computer scientists either).

Tracking from Kinect seems a bit too challenging - it's not going to
work if dancing with a partner, and if there is no partner, we might end
up with just a version of Dance Dance Revolution.

I liked the idea of voice prompts to the dancer - an earpiece could
issue a sequence of instructions, for example a series of Ceroc moves -
sufficiently ahead of the music to guide someone (like me) who relies on
a teacher shouting what to do next.