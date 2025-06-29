Client: [Cambridge Consultants](Cambridge_Consultants "wikilink")

Contact: Alistair Morfey <alistair.morfey@cambridgeconsultants.com>

An increasing number of our projects need to include embedded security.
This is particularly true as more devices expect to support remote
software upgrades in the field throughout their installed life. We see
this a lot in smart metering. Many of these devices are battery-powered
and need to implement modern security algorithms at low energy. There
are open source libraries available for symmetric (e,g AES-128) and
asymmetric (e.g ECC 256 primes) crypto algorithms, but they are mainly
aimed at computers and require far too much memory and energy. We have
found good open source libraries for symmetric crypto algorithms that
are suitable for low energy use in embedded systems with small memories.
However we have not been able to find any suitable libraries for
asymmetric crypto algorithms such as ECC-256p. The challenge is to
develop such a portable code set for an embedded 32-bit or 16-bit
processor with a small amount of memory (code flash and data RAM). It
should identify clever techniques to minimise energy usage and memory
requirements. It should be made available as open source software.

feedback

Do you think that this project would be feasible on the ARM core used in
the Raspberry Pi?

All students have their own Raspberry Pi this year (just for hobby use -
we don't do any teaching on it), so this would be a reasonable target
for a low-power implementation.

However, to make the project feasible for a group project, we might need
to anticipate plausible ways that it could be divided among a team of 6.
At present it looks more like a one or two person project.