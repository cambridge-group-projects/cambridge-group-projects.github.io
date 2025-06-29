We are increasingly deploying our telephony systems in cloud
environments as that allows us to increase and decrease capacity
elastically in a way that has never before been possible. In the past,
the only way to cope with peaks in demand (such as during X Factor
voting) was by engineering in lots of capacity which of course adds
expense. One of the challenges of an elastic system, though, is that it
can take of the order of ten minutes to bring a new resource on-line, so
judging when to increase capacity is not straightforward. If you bring
the resource on-line too early the carrier faces increased costs, but if
you bring the resource on-line too late calls will fail and the carrier
faces lost call revenue and upset customers. To make matters more
interesting, resource cost may not be fixed, but may have steps or vary
by demand and/or time of day.

This project would define an algorithm (or algorithms) to decide when to
add and remove (‘orchestrate’) resources in the cloud to balance the
competing pressures of cost and customer service.

We will provide datasets that can be used to train the system and to
test how it behaves with new data.

Feedback: An interesting challenge, but I don't think it would be easy
to divide this among a team of six. Is there some other way that a team
might create a demonstrator based on the data sets that you have?