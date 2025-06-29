Are ideas with hardware in scope? A recent BBC Click programme reported
cheap sensors for people entering and leaving rooms. The way they said
it suggested it picked up mobile phone signatures. The idea that you
might be able to cheaply count the mobile phones in the room is
intriguing from several perspectives, not least to do with audience
polling. But it could also be a useful proxy for occupancy in our room
utilisation problem. I can’t remember the price at which Steve Young
said he would want to equip all teaching rooms, but I have £100 in my
head. We have something in the order of 500-600 teaching rooms so that
would be £50-60K which sounds reasonable.

Would designing and building a prototype system be a CL project or
should it be something for Engineering..?

One of the teams did something related last year ...

<https://wiki.cam.ac.uk/cl-design-projects/Location-based_teaching>

We might be able to use that infrastructure for a utilisation project,
but would need to extend it with enough functionality to provide things
for different members of the team to do.

Not quite the concept I had in mind as the beacon is passive and the
phone app does the work (and holds the data). The main challenge for
this concept in the context of my room occupancy goal would be to create
the app that used the beacon and which all students and staff would want
to install, then get permission to collect location data.

One idea might be a cell phone signal booster like this:
<http://www.amazon.com/Sprint-Airave-Airvana-Version-reception/dp/B00B18LKU4>

You could then record how many unique connections you pick up. There is
probably a better idea. I don’t know enough about how phones pick up
mobile masts. Essentially you would be ‘sniffing’ for an active mobile
phone. Of course you would need to let people know you were doing this
and they would have the option of switching their phones off.

I guess another possibility would be to use Eduroam registrations - if I
remember correctly, there is quite a lot of data exchanged with the
local access point. Are you familiar with what this is?

(It would assume that the mobile devices are using WiFi, but this is a
reasonable constraint for building a demonstrator - it’s much easier for
us to get access to WiFi traffic than GSM traffic)