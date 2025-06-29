contact "HAJ-NAJAFI, Arran (NHS DIGITAL)" <a.haj-najafi@nhs.net>

Too late for 2019, but possible for 2020:

<https://digital.nhs.uk/> Client: Rob Sinclair, [NHS
Digital](NHS_Digital "wikilink")

Unknown waiting times either in an emergency or outpatient clinics cause
anxiety and frustration to patients. Develop an application that
provides a personalised waiting time that can be controlled by
clinicians to allow patients not to be tethered to the waiting room but
are notified in advance when to return to ensure a smooth flow through
the service resulting in a better patient experience and less congested
waiting rooms.

Three suggestions for 2019:

#### Models deployment

Models deployment NHS Digital use routinely collected data to build
models to support NHS. Some of these are predictive models identifying
high risk patients, the models themselves do not contain any sensitive
or identifiable information. We invite you to explore/build tools to
support the implementation and deployment enabling NHS Digital to share
these models with health bodies so they can run these models at their
end with minimum development work required. Model Background – Did Not
Attend (DNA) are estimated to cost NHS over £1B a year. NHS Digital has
explored HES data, and used feature engineering to build random forest
models to identify patients at high risk of not attending an
appointment. The output of the above machine learning model is a list of
variables with estimates (i.e. gender; male = 0.234, female = 0.145).
These models are to be run on booking data which Trusts hold with
predictors and additional information on appointment. This will produce
a RAG rating for every attendee i.e. Red – high risk of DNA, Amber –
medium risk and so on. Challenge - There are multiple IT suppliers and
various booking systems that Trusts use. These booking systems will have
different formats and data quality issues amongst others. We invite you
to explore how this model (R/Python script) can be executed on booking
data at Trusts end with minimal development required for the Trusts. The
model does not have any identifiable/sensitive information. However, the
booking systems may contain personal, identifiable and/or sensitive
information.

#### PoC - Live A&E attendance app for public

Emergency Care Dataset (ECDS) contains hospital code, hospital postcode,
Accident and Emergency attendance amongst other variables. Create an app
that is updated in real time showing attendance at any Accident and
Emergency site to enable patients to make informed choice on which A&E
site to visit when required.

`* Could you clarify whether some part of the ECDS data is available as a realtime feed, or would it simply be used to train a predictive model for triage estimation?`

Some kind of back end functionality seems necessary. We did discuss this
one with one of his team in a call I had earlier in the summer. I think
the plan was that the static dataset would be used to build a predictive
model for improved interactive triage.

#### Enabling Independent Living for an ageing population.

When the NHS was founded in 1948, 48 per cent of the population died
before the age of 65; that figure has now fallen to 14 per cent. Life
expectancy at 65 is now 21 years for women and 19 years for men and the
number of people over 85 has doubled in the past three decades. By 2030,
one in five people in England will be over 65. This success story for
society and for modern medicine has utterly transformed our health and
care needs. Many people stay healthy, happy and independent well into
old age, and there is mounting evidence that tomorrow’s older people
will be more active and independent than today’s.

The right supply of housing in terms of location, affordability, size,
tenure and facilities is a crucial factor in enabling people to remain
in their own homes as they age. It is essential that new housing stock
reflects the needs of the local ageing population, with sufficient extra
care, sheltered and age-friendly housing available . Existing housing
stock can also be adapted with aids and technology to assist older
people with daily living and maximise their independence and safety.
Adaptations and care packages can aid older people’s recovery after a
hospital stay and can help them to remain in their own homes at the end
of life. Providing adaptations to support an older person to remain at
home for just one year can save £28,000 on long term care costs.

We invite you to build IoT tools to support Independent living for older
adults cognisant of the fact that people over 55 make up 94 per cent of
non-users of the internet (Centre for Ageing Better).

Idea led to [Grand Remote](Grand_Remote "wikilink")