Client: Steven Johnston, Microsoft Research <v-stejo@microsoft.com>

The aim of this project is to produce a highly accurate map of the
Cambridge cycle network including information about inclines, one way
roads, restricted access. Since this will require more data than can be
gathered using a simple GPS device or smartphone this project will have
a custom hardware element based around the .NET Gadgeteer platform. The
first part of the project will build a device to capture data such as
GPS, accelerometer, compass, cadence, wheel rotation, heart rate etc, to
produce a sample dataset representative of the Cambridge cycle network,
as well as providing the cyclist with relevant data.

The second part of the project will process and visualise the sample
dataset. This will include removing erroneous data, fusing data streams
and maps to improve accuracy and inferring cycle features from the data
whilst keeping an emphasis on data accuracy. This information could be
used to recommend cycle routes or diversions in real time, assist with
finding a bike rack, or perhaps the addition of new cycle lanes. The
resulting dataset should be open and accessible.

Note that Gadgeteer development requires .NET tools, so the development
language for this project will either be C# or VB.