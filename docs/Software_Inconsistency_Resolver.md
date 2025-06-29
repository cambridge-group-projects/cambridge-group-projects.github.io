Proposed by Jasmin Jahić <jj542@cam.ac.uk>, to be discussed with Chris
Cooper-Bland of Endava for 2026

This is currently phrased as a research project, so a specific problem
and technical approach would need to be defined.

Your task is to make a architecture design consistency tool, probably
based on LLM technology, that works on the different levels of
abstractions. In its basic instance, the tool works with a model of
software architecture and source code. It identifies parts of code
belonging to abstract architectural components, suggests issues with
breaking isolation, updates all the identifier names in a code base, for
internal consistency and to ensure agreement with software architectural
model (interfaces, component names, identifiers, other specifications).
To create a software architectural model, we will use draw.io as the
tool, as it enables generating clean xml from a visual representation.
Besides the main goal of the project, the students will have the
opportunity to explore:

\- Can LLM read binary on any level and extract any software
architecture-relevant information?

\- Can LLMs enable control of source code from architecture (e.g.,
"notice" any change in architecture and suggest changes in the source
code)?

\- Can LLMs enable updates to architecture model based on the source
code (back propagate any change from source code and conclude if
anything should be changed in the architecture)?