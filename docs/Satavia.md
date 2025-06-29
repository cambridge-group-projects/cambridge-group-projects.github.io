Contact: Dr. Adam Durant, CEO; adam.durant@satavia.com

Proposed with [Microsoft](Microsoft "wikilink")

[Predictive aircraft
maintenance](Predictive_aircraft_maintenance "wikilink")

Local company Satavia helps airlines to schedule engine maintenance
based on the amount of exposure the components have had to air
pollution, dust, volcanic eruptions and other factors. They have large
data sets which could be used to train predictive models that might be
added to the Microsoft Cortana Intelligence Solution Template Playbook
for predictive maintenance in aerospace. You will need to deliver a data
ingestion architecture for a range of global data, and also demonstrate
an aircraft maintenance scheduling application that applies the results.

Feedback:

Unfortunately, I don’t think that second year undergraduates have any
significant technical knowledge of time-series analysis.

They should be familiar with basic statistical regression, but will not
have much understanding of machine learning techniques until third year.
I don’t believe that we teach much in the way of frequency domain
analysis or autocorrelation methods in the Computer Science degree -
these are topics that would be more typical of the signal processing
courses taught in Electrical Engineering.

I’m afraid I can’t advise on which features of Cortana would be most
relevant to your problem, as I have not used the product myself.
However, Google suggests that the “Cortana Intelligence Gallery” might
contain relevant stuff:
<https://gallery.cortanaintelligence.com/Experiment/Time-Series-Forecasting-8>

If I understand correctly, this example simply uses Azure to host an R
script, but it should be relatively trivial for students to follow these
instructions (if they found them!)

So to make this into an interesting design challenge, we would need to
give some thought to technical infrastructure, delivery mechanisms etc,
that are appropriate for your user base. It’s unlikely that any members
of the team would have any prior knowledge of the aircraft maintenance
industry, so we would need to come up with a relatively trivial use case
that is sufficiently representative of the business issues to be
interesting.

Original suggestion:

Environmental factors in the atmosphere, like dust, ice, sulphur, and
volcanic, accelerate wear of aircraft components. Modern aircraft
generate large volumes (several GB) of data per flight and digital
predictive analytics technology has great potential to support asset
health monitoring, and disrupt traditional maintenance and flight
planning processes. The solution combines high spatio-temporal
environmental factor analysis with machine-learning to provide advanced
risk-based decision-making capability.

Data driven model predictions (in this case Satavia’s environmental
factor analyses) inevitably contain some level of uncertainty, due to
the reliance on a finite (typically small) sample of direct
observational measurement data, or coarse resolution input
meteorological data used to drive the NWP model. The project will
demonstrate advanced environmental data analytics capability through the
application of artificial intelligence (AI) techniques such as
reinforcement learning (RL), to develop a framework for sequential
decision-making under uncertainty. The objectives will include:

1\. Improve the skill of the NWP-based model using training data
acquired from a local in situ measurement network; 2. Correlate aircraft
environmental factor exposure to component wear rates and proxy data
provided by engine health management; 3. Develop autonomous
decision-making capability to adjust aircraft flight plans and engine
maintenance plans in near-real-time.

Aircraft original equipment manufacturers (OEM), operators, and
maintenance repair organisations now increasingly share maintenance
liability through ‘power-by-the-hour’ services for the lifetime of the
aircraft. Unscheduled maintenance costs the industry billions of dollars
each year (e.g., in 2016 sulphurous air pollution cost Rolls-Royce
>£65M) and causes disruption to airline operator flight schedules.
Customers currently implement highly conservative maintenance schedules
at pre-defined maintenance frequency. Predicting when to do the
maintenance based on environmental exposure could make huge savings for
the industry. Satavia’s data-as-a-service enables aircraft operators to
modify aircraft flight plans and scheduling to extend engine lifetime,
while engine manufacturers can proactively adjust maintenance plans to
minimise unscheduled maintenance. Satavia is currently working on a
series of ‘proof-of-value’ projects with a UK-based aircraft engine
manufacturer.