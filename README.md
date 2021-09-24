# SmartGasSensing

This is an application of deep learning to gas sensor's data. The dataset we are using was retrieved from the UCI Machine Learning Repository
(https://archive.ics.uci.edu/ml/datasets/Twin+gas+sensor+arrays) and contains the readings of an 8-sensors array which is exposed to 4 volatile organic compounds
(Carbon Monoxide, Ethanol, Ethylene, Methane) at different concentration levels [1]. The gas sensor array (GSA) provides a unique fingerprint upon exposure to a
specific gas stimuli.  In this application we are using a multioutput 1D Convolutional Neural Network in order establish a function approximator which will
eventually take as input the fingerprint produced by the GSA and outputs information about the nature of the gas stimuli (type of gas and/or concentration).

This work is under constant development as it needs further investigation regarding the predictions of the concentration values of each gas stimuli.

[1] J. Fonollosa, L. Fernandez, A. Gutierrez-Galvez, R. Huerta, S. Marco. 'Calibration transfer and drift counteraction in chemical sensor arrays using Direct
Standardization'. Sensors and Actuators B: Chemical (2016)
