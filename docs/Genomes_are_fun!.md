Client: Keira Cheetham,
[Illumina](Illumina "wikilink")<KCheetham@illumina.com>

Contact: "Oldham, Scott" <soldham@illumina.com>

Design and implement a game (on iOs and/or Android) to teach the user
about genomes or genomic sequencing, targeted to a GCSE or A level
science student. The game should have a strong social element to it.

One suggested game could be bacterial genetics, where each user has a
'pet bacterium' with certain continuous characteristics, eg shape, size,
ability to survive on a wide range of foodstuffs, resistance to
antibiotics. Bacteria can exchange parts of their sequence (the social
aspect) and the challenge is to evolve the overall fitness of your pet
bacterium by interaction and exchange with others. The user can select
which small part of the bacterial genome to exchange with a friend.
Eventually users will be able to work out which parts of the bacterial
genome define which of the characteristics and move up the leaderboard
of 'fit bacteria'. (mobile apps, graphics, social networks, no
background in biology required)

## feedback

I was thinking about ways to add a little more technical challenge to
this project. One thing I considered is that we might exploit the
potential of the Raspberry Pi as a very low cost compute server to do
far more extensive genetic algorithm optimisation. Each "player" could
leave their Raspberry Pi running for a week or two, then (the social
aspect) carry them to a shared location and connect them together with a
network cable to exchange genetic material. I think that negotiation of
an ad-hoc local network will involve a bit of low-level technical
challenge (though must check this with a networks specialist), and I
like the symbolism of using a physical connection to transfer the
genetic material.

Rather than bacteria, do you think we could use something more
Internet-friendly? Hamster-kitten-panda hybrids or something? We could
use a lot of compute power to optimise the fur :-) However, the fitness
function might be a little more complex than for a bacterium.

## response

The bacterial model fits well with the physical exchange of 'DNA'. To
liven it up, users could try to make the most
pathogenic/contagious/antibiotic resistant bug that can live on as many
substances as possible (soil, empty coke cans, fingernails), has the
most rapid growth etc. If you feel that soft and fluffy has a wider
audience appeal then I'm happy for the project to be a hybrid pet or
alien creature (or anything else)! Presumably the genetic algorithm can
be as complex as we/you/the students choose it to be.

## more

I had two things in mind here - one is broadening appeal, which I've
been discussing with the Vet School in Cambridge lately, and the other
is that I'm reluctant, in educational contexts, to suggest that genetic
algorithms work in very much the same way as actual biological
processes. Use of more playful examples (or as you suggest, "aliens"),
may help to avoid this - whereas using bacteria may give the impression
that we're building an actual biological model.