Contact: contact Owen Coombs (owen.coombs@baesystems.com)

[Reinfection Monitor](Reinfection_Monitor "wikilink")

Original suggestion ...

No-hassle internet security

Client: James Dickin, BAE Systems Applied Intelligence
james.dickin@baesystems.com

How easy do you find it to set up and maintain internet security on your
computer? How about your parents? Or your grandparents? For some people
setting up and maintaining anti-virus software, differentiating between
real and fake pop-up security warnings, recognising the difference
between genuine and phishing emails and keeping their computer
malware-free is an insurmountable challenge.

ISPs struggle to differentiate themselves solely though pricing and
connection speeds so increasingly look for “value add” features that
they can offer their customers. An ISP could offer their customers
“no-hassle internet security” in the cloud, in the user’s home router or
in the form of a “dongle” that sits between the user’s computer and
their home router.

Produce a prototype of this security dongle using a standard desktop
computer with two Ethernet interfaces – one internet-facing and one
user-facing. The dongle should be zero-maintenance and must protect the
user from virus, malware and email threats, taking sensible action to
protect the user without confusing them.

Feedback:

From this description, I'm not completely certain of the intended scope,
and whether it would be feasible for an undergraduate team to achieve
anything along these lines within 7 weeks. The functionality described
for the "dongle" seems very close to that of a conventional firewall,
but with additional intelligent features that would outperform existing
spam filtering services. Have I misunderstood?

Response:

Thanks for the feedback. I've received the following from my colleague
James Dickin, who proposed the project idea.

"Alan's understanding is correct. I deliberately left the form of the
solution in my description quite open however so that the students could
propose their own solution to the problem I presented.

I was hoping that the students might, for instance, write code that
pipes the user's data through industry tools such as ClamAV (Linux
antivirus) and SNORT (Linux intrusion detection system), modifying it as
appropriate when threats are detected. They could write stubs for the
industry tools to emulate the detection of threats so that they don't
have to handle infected data. The data modification in response to
detection is the most interesting bit and the place where the students
could do the most innovation.

They actually don't need to use a stand-alone machine with two Ethernet
ports - if they want to use the university's existing dev systems they
could run this either as a VM or just run it on the same machine as the
'user'.

Alan makes a fair point on the feasibility of the students achieving
anything in the 30-60 hours they're expected to spend on this project
however - I'd guess that even the simplest solution to this problem
could take more time than this."

More feedback:

I think you're right - data modification in response to detection would
be an interesting challenge, perhaps more than the routing and
configuration involved in piping the data through standard Linux tools.
I believe that most current firewalls simply block infected content, or
at best offer the user a yes/no decision for which the user must pay
attention and take responsibility. What kinds of data modification do
you think might be feasible, and what threat models would be addressed?
I guess we need to think of a scenario in which (say) a phishing email
contained some data that might still be of value to the user - or else a
situation in which a normal email has been mistakenly classified as a
phishing email, but has some other automated action taken.