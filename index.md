# What is the project about?
This project is about to provide the general purpose environment that allows biologists and other
domain experts to use transparently state-of-the-art techniques in machine learning to improve
their image segmentation results.
ImageJ is a public domain Java image processing program extensively used in life sciences.
Active Segmentation plugin is the redesign of existing Trainable Weka Segmentation (TWS) of
ImageJ. The main functionality of the platform was already developed in the context of GSOC
2016 but the platform is still under development. In last Google summer of code, the major
focus was on integrating generic filter families and specifically on one family of filters i.e.
Gaussian Scale Space.
The Active Segmentation provides generic functionality and user friendly interface so that the
user can include the state of the art filters and machine learning frameworks from the WEKA
library:
● Active learning.
● Multi-instance learning designed by third party in a robust manner
In this Google summer of code we need to expand the existing functionality of the Active
Segmentation plugin. The Generic framework can be used for segmentation, classification and
object detection but in last Google summer of code the Segmentation has been completed, we
need to extend this platform to provide functionality like classification and object detection
