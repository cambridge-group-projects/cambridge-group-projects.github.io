Argon Design has now been acquired by [Broadcom](Broadcom "wikilink") -
see that page for follow-on projects.

### 2020

No proposal. Alan Scott <alan.scott@broadcom.com> expressed interest
for future years.

### 2019 proposal

Project was [Meeting Zoom](Meeting_Zoom "wikilink") with client Imdad
Sardharwalla imdad.sardharwalla@argondesign.com

#### original suggestion

In a group call, Skype and Google Hangouts let you know who's talking by
illuminating the speaker's name. But what if many of the participants
are in the same room? Perhaps seated around a conference table? Your
goal is to develop a system that is tailored to this scenario--it should
be able to determine the speaker in a room of participants, and indicate
them on a simple map of the room. Your client will provide a microphone
array for you to work with.

#### feedback

(title - Room-Meet?)

I like the idea, and it’s nice for students to have a chance of working
with a microphone array. I haven’t used these myself - what kinds of
signal processing might students need to do, in order to achieve spatial
localisation?

I would expect that one or two members of the team might focus on the
localisation problem, in which case we’d need to think of other system
aspects that the rest of the team might work on. For example, maybe it
would be feasible to use a single wide-angle camera (or perhaps two or
three, to cover a round table), and automatically zoom the video image
in to the current speaker? Simple algorithms for face recognition might
be sufficient to estimate the camera geometry in relation to audio
localisation model.

### 2018 project

Contact: 'Steve Barlow' <steve.barlow@argondesign.com>

Client: Jack Haughton <jack.haughton@argondesign.com>

[Augmented Reality Furnishing](Augmented_Reality_Furnishing "wikilink")

### earlier ideas

I confirm we’d like to put forward a brief for a project for next year
(Lent 2018).

My delay in replying was because I was chewing over ideas for possible
projects. I’ve still not had an idea I’m really happy with so I thought
I’d better reply now and then keep thinking.

An FPGA project is nice because it’s different technology. The downside
is it takes more work to develop compared with software and so might not
do something as obviously impressive. The reasons you would use an FPGA
are if you ultimately want to implement something in hardwired logic for
lower power or you need throughput or low-latency that is beyond a
software solution. My current thought is a hardware corner detector that
could provide input to a software SLAM algorithm.

I know Simon Moore from a number of years ago, when he was working on
asynchronous processors. What FPGA boards do you have? I might
alternatively provide a board if that is an easier way of connecting a
camera and not having too many FPGA resource constraints.

Another possible non-FPGA project direction is “slow cameras”. If you
only capture an image every hour, you can spend a long time doing image
processing on it on a microcontroller. You don’t need a powerful system.
So what could you do to create smart sensors using this?

I’ll continue to think over the next couple of months.

### response

Simon Moore does still teach undergrad classes with FPGA boards, and we
have quite often used these in the group design projects in the past. As
you say, it is usually a little more difficult to bootstrap novel FPGA
code to the level of getting an impressive application result, but our
audience do appreciate the challenge, and give students credit for their
achievements!

Information on their FPGA course is here:
<http://www.cl.cam.ac.uk/teaching/1718/ECAD+Arch/>

They start with SystemVerilog, then FPGA synthesis using Altera Quartus
and Qsys tools. The hardware is a DE1-SoC board from Terasic with our
own custom I/O attached.

There are some further details of the hardware here. It looks as though
it includes an LCD touch panel, but no camera input
<http://www.cl.cam.ac.uk/teaching/1718/ECAD+Arch/additional.html>

Terasic seem to provide accessories including image capture devices:
<http://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=65#Category68>

Hardware feature detectors for SLAM sound ambitious for undergrads! But
would be exciting if this is feasible. If you want to pursue that, I
should probably introduce you to one of Simon’s team, to discuss the
level of skill that can be expected from students. I’ve had undergrads
use SLAM libraries, but wouldn’t expect them to have much detailed
understanding of the implementation in second year.