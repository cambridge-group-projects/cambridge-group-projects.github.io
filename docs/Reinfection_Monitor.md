Client:James Dickin, [BAE Systems Applied
Intelligence](BAE_Systems_Applied_Intelligence "wikilink")
<james.dickin@baesystems.com>

A constant problem for PC owners is that, even after someone helps them
remove a malware infection, they soon repeat the same action that caused
the infection in the first place. And because malware doesn't usually
advertise its existence, the user never learns how to stop it happening.
The goal of this project is to create a network monitor dongle (possibly
prototyped on a Raspberry Pi) that can simply be inserted as a router
between the PC and home router, and will identify the network traffic
that is characteristic of a particular piece of malware. It can be
configured and left in place by the technician who cleans up an
infection, and will send that person an email as soon as a reinfection
is spotted (of course, it should also notify the user, provide a visible
warning on the unit itself, and provide a local status report that can
be accessed from a browser, with details helping users to understand
what has happened). Some knowledge of networking on Linux will be
required.