# Implementation of PCA and ICA

Implementation of PCA (Principal Component Analysis) and ICA (Independent Component Analysis) from scratch.

### PCA (Principal Component Analysis)
- Implements Principal Component Analysis from scratch on the MNIST Dataset. It converts each image into a 784-dimension vector. Since it is a 28 x 28 image, we get 784 pixels.
- I split the training dataset in a `80:20` ratio for training and testing respectively. I perform PCA on the training data and then use k-Nearest Neighbors to test the testing data.

### ICA (Independent Component Analysis)
- Implement Independent Component Analysis to mix 2 signals i.e. a sinusoidal wave and a ramp wave.
- I mix them using a mixing matrix and then perform ICA to get the independent components.

The mixing matrix:
        [ 1  0.5]       
        [ 0.5  1]   
