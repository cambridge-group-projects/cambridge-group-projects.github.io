Client: John Bain, Cisco <jbain@cisco.com>

A key consideration in the design of video-conferencing systems is to
minimise the latency added to the video and audio, since this can have a
marked effect on the naturalness of communication. Many software
solutions exist for measuring various aspects of the system latency, but
there is no substitute for end-to-end (often called glass-to-glass,
referring to the lens of the camera and display screen) measurements of
video and audio latency. This type of measurement has traditionally been
subjectively measured by humans, and is hence prone to error and bias.
Your task is to automate this by presenting an audio plus video signal
to one end of a video-conference link, and measure the latency of the
screen/speaker output at the other end. The two ends may be
geographically separated - even in different continents. The Altera
teaching board will be used to provide I/O facilities. Some technical
ingenuity will be involved in ensuring that any delays or offsets in
measurement are accounted for.