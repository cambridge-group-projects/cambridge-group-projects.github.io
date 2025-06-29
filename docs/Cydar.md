The client is rob.hague@cydar.co.uk

[Surgery in the Cloud](Surgery_in_the_Cloud "wikilink")

Original proposal:

Visualizing Clouds

At Cydar, we make extensive use of Amazon Web Services. In particular,
we use their Virtual Private Cloud (VPC) features to set up many
separate virtual networks, each containing a number of virtual machine
running different software for different purposes. The connections both
within and between these networks quickly become complicated. Moreover,
as we’re dealing with highly confidential patient data, we need to be
sure we have a good understanding of how the network is configured and
where the data is going at all times.

The brief is to create a tool for visualizing VPCs in some kind of
automated block diagram. It should show, at a minimum: - Connections
between machines within a VPC - Routes in and out of each VPC (as
governed by AWS Security Groups)

The visualization should update automatically as the network changes.
Once the basics are in place, there’s plenty of scope for additional
information such as: - Real time network traffic display - Server health
monitoring - Interaction, for example to focus on more details of a
particular VPC

Cydar will be able to provide technical help in integrating with AWS, as
well as example networks to visualize.