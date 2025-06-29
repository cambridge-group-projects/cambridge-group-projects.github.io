Client: Theo Markettos, Computer Lab <theo.markettos@cl.cam.ac.uk>

We have a LitePlacer robot that can automatically assemble circuit
boards (https://youtu.be/t__ybwOufyg), with a machine vision system
based on OpenPnP. Unlike many computer vision problems, the cameras
could in principle be moved around, getting better field of view or
details of specific regions. Our robot currently uses the vision
capabilities for simple tasks such as recognising board features and
component tapes to align components it is placing. We would like to
extend the capabilities of the system to automate the setup of the
machine, for instance printing part numbers from CAD data on sticky
labels that the vision system reads; configuring placement of component
tapes; recognising parts from their shape or markings to rotate the
tape; detecting parts and boards from text printed on them; and guiding
the user through setup with augmented image views.