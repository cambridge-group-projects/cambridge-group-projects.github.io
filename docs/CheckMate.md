Client: [Illumina](Illumina "wikilink") Contact: "Oldham, Scott"
<soldham@illumina.com>

Personal genome sequencing is now available to the masses! An individual
human's genome sequence contains 3 billion bases. It can be represented
as either a string of characters or as a graph showing where the
sequence deviates from a standard, reference genome. Your task is to (1)
write a tool to filter/compress such a file into a representation of the
genetic status for a (provided) selection of serious diseases of an
individual, such that it can be stored on a Raspberry Pi or smartphone,
and (2) write a Raspberry Pi or smartphone app that can securely
communicate with another to establish whether the two individuals
represented share genetic status of any of the diseases considered.

For bonus points: The genetic details of one individual should not be
revealed to the other individual - beyond reporting that the two
individuals do or do not share genetic status for one or more diseases.

Appendix: Illumina stores variant calls resulting from the sequencing of
a genome in a standard format (gVCF) file. Most healthy individuals are
carriers of one or more mutations that, if present in two copies (i.e.
inherited from both mother and father), would result in a serious
disorder (eg 1 in 29 Caucasian Americans carries one mutation in the
cystic fibrosis gene :
<http://www.cff.org/AboutCF/Testing/Genetics/GeneticCarrierTest/>).