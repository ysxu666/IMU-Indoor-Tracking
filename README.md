# Overview
In this project,You can utilize Machine Learning or Deep Learning for IMU-based Robot Indoor Tracking, including the model design, training strategy, etc.

# Description
Indoor tracking is a crucial topic in our daily lives, whether it is for pedestrians or robots. Considering the scenario that you go to a completely new shopping mall and get lost in it, an indoor tracking or indoor navigation system would help you a lot. Among all of these indoor tracking methods, inertial measurement unit (IMU) attracts much attention. With accelerations, gyroscopes, and magnetometers, IMU can record the variation of the movement and thus map to the moving trajectory of the object.

In this personal project, we will focus on IMU-based indoor tracking for wheeled robots. More details will be given below.

##1. Dataset Description
The dataset contains four parts: Training Set, Validation Set, Test Seen Set, and Test Unseen Set. We will give you the raw data and ground truth of the Training Set and Validation Set for training the model. Only raw data from the Test Seen Set and Test Unseen Set are for the model evaluation. Training Set, Validation Set, and Test Seen Set are collected in the office:
