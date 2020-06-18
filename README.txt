
This project is based on Airfoil Self-Noise Dataset from UCI Machine Learning Repository. This is a regression problem. Here, goal is to predict Scaled sound pressure level of the airfoil, in decibels based on the other available data. Artificial Neural Network (ANN) in PyTorch is used here

This NASA data set comprises different size NACA 0012 airfoils at various wind tunnel speeds and angles of attack. The span of the airfoil and the observer position were the same in all of the experiments.


Attribute Information:

This problem has the following inputs:
1. Frequency, in Hertzs.
2. Angle of attack, in degrees.
3. Chord length, in meters.
4. Free-stream velocity, in meters per second.
5. Suction side displacement thickness, in meters.

The only output is:
6. Scaled sound pressure level, in decibels.


--------------------------------------------------------------
Results:

RMSE of test set: 0.27997715045769067

RMSE of training set: 0.2614866052719937

MSE of training set:  0.0690247192978859



