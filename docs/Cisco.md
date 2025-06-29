The contact email for John Bain is jbain@cisco.com

# Finalised brief

- [Measuring glass-to-glass video-conference
  latency](Measuring_glass-to-glass_video-conference_latency "wikilink")

# (old) discussions

## Introduction

In 2011, Cisco Systems offered an undergraduate group project to design
and implementation an on-line testing system, involving the design and
implementation of a new programming language.

The six students that worked on the project produced a complete and
effective system which is now being considered for live use by another
company. Hoping to continue the success of last year, Cisco Systems –
represented by John Bain and Edd Inglis – are happy to put forward the
following idea for another project.

## Background

The Cisco site in Langley specialises in multipoint video-conferencing
systems, designing hardware and associated software to allow many video
endpoints to communicate in large-scale conferences. One key
consideration in the design of such systems is to minimise the latency
added to the video and audio, since this can have a marked effect on the
naturalness of communication.

Many software solutions exist for measuring various aspects of the
system latency, but there is no substitute for end-to-end (often called
glass-to-glass, referring to the lens of the camera and display screen)
measurements of video and audio latency. This type of measurement has
traditionally been subjectively measured by humans, and is hence prone
to error and bias.

## Proposal

We would like a team to create a system for measuring end-to-end latency
of video and audio in a point-to-point or multi-point video conferencing
call. We envisage such a system will include a light emitter and
matching light sensor, and a sound generator and receiver, though any
equivalent ingenious solution would be equally applicable.

The system would obviously need to be operable on systems closely
located in a testing environment, but consideration should be given to
testing between geographically separated devices. This is illustrated by
the diagram below, where perhaps endpoint A is in London and endpoint B
in San Jose.

## Equipment

We imagine this system could be developed in a number of different ways.
Our anticipation is that a small, embedded device would provide the most
appropriate starting point for this, but are happy to entertain other
suggestions. Assuming an embedded platform is chosen, we are happy to
supply the appropriate hardware - for example an Arduino clone or
similar development board - or for students to use any other platform
they may be familiar with from other parts of their course.

It should be possible to do complete testing of such a system using
PC-based video endpoints, but we can also supply ‘real’ endpoints and
conferencing infrastructure for testing towards the latter stages of the
project if desired. (We anticipate an embedded platform will need the
following peripherals at a minimum: ADC/DAC x2, GPIO, Network
(Ethernet). \]

## Notes to supervisors

We feel this project provides a number of different areas of
investigation and interest. Some of these include:

- Real-time operation; by its nature, this is a time-critical problem. A
  successful system could either be implemented at a logic level, by
  using an off-the-shelf RTOS, or even with an RTOS developed by the
  students
- Hardware and software; our engineers work with both day-to-day,
  meaning the project is realistic as well as more widely scoped. The
  system will solve a genuine issue, potentially offering more interest
  than a toy problem.
- Network enabled; interacting with IP networks is challenging and
  interesting, and will allow students to use network analysis tools to
  examine existing or new protocols for communication between remote
  devices.
- Time synchronisation; there is a need to synchronise remote devices.
  This could involve the use of NTP or other measurements of the
  round-trip time of the network, to allow accurate measurement of the
  true glass-to-glass latency.
- Robustness; the system needs to be robust in the face of noisy and/or
  corrupted audio and video, as well as lossy networks between remote
  measuring devices. This offers the opportunity for students to
  investigate methods of making the system robust to errors and external
  network factors.