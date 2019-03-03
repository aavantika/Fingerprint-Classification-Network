FPSensorNet: It is a fingerprint sensor classification network based on ResNet50 architecture. We have tested this network on  databases like FVC2002,FVC2004,FVC2006, IIITD-MOLF and IITK. Since the type of fingerprint sensor in each database is varied thus different models ( having similar architecture but different last FC-layer) have been trained. In the below code we are providing model trained on IITK single fingerprint data. 
===================


This README will guide you through running the code and getting classification results on test images.
This code is for classifying IITK single fingerprint data consisting of three sensor data i.e Futronics, Lumidigm and SecuGen.
This code is implemented by  avantika singh ( student of Indian Institute of Technology, Mandi).

----------
For testing purpose some of the images belonging to IITK single fingerprint data is kept in images folder.

----------

Steps
-------------

> - Run the python code FPSensorNet.py
> - A text file 'result.txt' will be created with the classification results of the images

Required Dependencies
-------------

> - Python
> - Numpy(1.13.1)
> - Keras(2.0.7)
> - h5py(2.7.0)






