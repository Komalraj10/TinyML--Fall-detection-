﻿# TinyML--Fall-detection-

The objective of this project is to develop a real-time fall detection system using TinyML to enhance the safety of individuals, especially the elderly or those living alone or the children of the house.This can also be used for detecting fall in accidents. 
In the event of a fall, the accelerometers and gyroscopes on the smartwatch capture sudden and abnormal changes in motion.
The TinyML model analyzes the sensor data and quickly identifies the deviation from normal movement patterns associated with a fall event.
Data collection:Using Edge Impulse 
In the first step,we collected real time data using edge impulse and gyrometer sensors present in mobile phones.
Using that data we trained the model to catogerise our data as fall or not fall.
Decision Tree Model used for classification:
Classification of fall or not fall is done using the following tree and implemented using the given python code.
Wrote the .imo file in arduino ide in order to pass the parameters of DT model used in ML to integrate ML with arduino Nano.
