Client: Pete Steggles, [Ubisense](Ubisense "wikilink")
<Pete.Steggles@ubisense.net>

Our sensor system (https://www.ubisensedimension4.com) can be used to
locate tools and cars on production lines, storing measurements and
derived locations for audit purposes. Every day each factory generates
~2e8 locations from ~1e9 raw measurements. There is an
environment-dependent function from tag-to-sensor distance/bearing to
sensor measurement probability/error, and an environment-independent
function from a set of sensor measurements/errors to the probability of
a ‘good’ tag location. Your task is to use the stored data to
characterize these functions, compare them across sites, and build a
planning tool to optimize future installations.