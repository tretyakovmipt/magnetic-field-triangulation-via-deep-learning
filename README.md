# magnetic-field-triangulation-via-deep-learning
Using synthetic data, we analyze if a neural network can determine a magnetic field vector in a hard-to-access region based on the reading from several sensors around the region.

# Results
So far I tried a 3-channel 1D convolutional neural network with the following architecture:

![Fig. 1](cnn_fig.png).

Channel one corresponds to an array of Bx components from all sensors.
