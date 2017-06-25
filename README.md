# Thesis_MaStat
Thesis 
Master of Statistical Data Analysis Thesis. 
-------------------------------------------
Abstract


Older people are a rapidly growing proportion of the world’s population is reported by National
Institute on Aging in 2015. Elderly people have a higher risk of death or injury resulting from
falls. A high proportion of over-aged population fall each year which can result into serious
health challenges. The increase in population of elderly people also increases the demand for
health care systems focused of elderly people.

The use of smartphones to detect fall events is a very popular method due to the decrease in the
manufacturing costs of smartphones as a result of the development of inexpensive Micro Electro
Mechanical System (MEMS) sensors. These sensors provide better computational capabilities
when compared to other wearable devices. Smartphones generally include the following sen-
sors: accelerometer, gyroscope, compass, magnetic field,proximity light and pressure sensors.
This allows different algorithms to be applied to increase the accuracy of any data required.

In this thesis, the recognition of and the differentiation between fall activities and activities of
daily living (ADL) was performed using a publicly available dataset, MobiAct and MobiFall.
The data set has captured inertial measurement unit (IMU) values for different ADL and Fall
activities. A large database was constructed to train and validate the model. For sensor, using
windowing technique the time domain and frequency domain (Discrete Fourier Transform) fea-
tures were extracted across each axis of motion. Feature selection methods were implemented
to reduce dimensionality, principal component analysis was used for exploration. Different clas-
sification algorithms like k-NN, decision trees, SVM were implemented and evaluated based on
their accuracy, sensitivity, and specificity to decide on the final model.

Furthermore, for the implementation of real time fall detection system we used Apache Spark
Streaming framework via pyspark.streaming module. Using basic TCP socket IMU signals
were sent to spark framework as data stream and using moving window the features were ex-
tracted for classification into one of the activities defined in the MobiAct dataset.
