Contact: Raoul-Gabriel Urma <raoul@cambridgespark.com>

2020 project: [Automatic Assessment of R
Code](Automatic_Assessment_of_R_Code "wikilink")

Draft:

Cambridge Spark is a startup that develops ​EDUKATE.AI​, a platform on
which students can access a collection of projects and receive immediate
automated feedback on their code -- KATE, the engine behind the
platform, evaluates functionality and code quality and generates
feedback to help students complete increasingly difficult projects,
improve their code and learn new skills. We currently support Python
(both standard Python and Data Science / Machine Learning applications)
and Java. The aim of this project is to develop a new service that we
can integrate into the platform in order to support projects in R.

Goal:​ The service needs to integrate with our system (see below for
technical constraints) so that feedback can be generated and help
students progress, learn and complete projects. Technical constraints...​
We have developed an infrastructure such that evaluation of code is done
as follows:

1\. Students write code either using our webIDE or using git on their
own machine

2\. When they submit code, a docker container starts. This image is
pre-built with a set of tests for the specific project they are working
on as well as a library that takes the code and the tests and extracts
data from them. Data includes a set of errors and failures generated
from the tests, relevant diagnosis about what was tested and why it
failed, information about code quality, etc...

3\. The data is then sent to another service that will process it and
render on the frontend of the application.

For this project, we will need to develop: ● An R library that takes:
source code written by students, tests written by a person developing R
exercises, runs it together with code quality tools and generate data in
a specific format (the format is well defined and will be shared upon
starting the project) ● Design a new format in which tests need to be
developed by the person developing a new exercise in order to be
processed by the service. This includes not only testing but information
about each test, such as what does it check for, what should be shown to
students in case of failure, etc... All this information will need to be
captured automatically by the library. If time allows, we can build an
SDK that will be shared with exercise developers allowing them to write
new exercises and tests faster and add them to the platform. ● Docker
configurations and script in order to build the standalone docker image
that has all dependencies required, tests preloaded as well as the the
service running with an entrypoint to generate feedback. ● A sample
exercise to demonstrate the service. This can be integrated to the
platform to test integration. If time allows, the exercise can also be
shared with users to run a user testing session.