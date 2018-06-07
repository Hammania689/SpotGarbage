SpotGarbage
===========
Paper can be found [here](http://delivery.acm.org/10.1145/2980000/2971731/p940-mittal.pdf?ip=128.2.177.146&id=2971731&acc=ACTIVE%20SERVICE&key=A792924B58C015C1%2E5A12BE0369099858%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1528403532_3a32befd40410dd3a51f4d2817bfe218)

Smartphone App to Detect Garbage Using Deep Learning
----------------------------------------------------

###Description
* The **SpotGarbage_GarbNet** folder contains the caffe model related files for **GarbNet**.
* The code to test GarbNet is given in files named **garbnet_demo** in HTML, standard Python and Jupyter Ipython Notebook formats.
* The code requires the following dependencies installed:
  * Caffe (CPU or GPU)
  * OpenCV
  * PIL
  * Numpy

###Instructions
* Put the images on which garbage needs to be detected in the **input** folder.
* Run the **garbnet_demo.py** or run the code snippets through the Ipython notebook.
* The predictions will be made and the images with garbage regions segmented will be saved in the **output** folder.

###SpotGarbage Apk
The SpotGarbage apk can be installed on any smartphone having Android OS 4.0.3 or above. It has been successfully tested on Nexus 5, Nexus 6, Moto G3, Moto X and Lenovo K3 Note with Android OS 6.0 (Marshmallow).

