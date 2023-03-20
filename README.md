# Implementation of PCA and ICA

Implementation of PCA (Principal Component Analysis) and ICA (Independent Component Analysis) from scratch.

### PCA (Principal Component Analysis) and k-Nearest Neighbors (kNN)
- Implements Principal Component Analysis from scratch on the MNIST Dataset. It converts each image into a 784-dimension vector. Since it is a 28 x 28 image, we get 784 pixels.
- I split the training dataset in a `80:20` ratio for training and testing respectively. I perform PCA on the training data and then use k-Nearest Neighbors to test the testing data.
- We test accuracy of the kNN model with

### ICA (Independent Component Analysis)
- Implement Independent Component Analysis to mix 2 signals i.e. a sinusoidal wave and a ramp wave.
- I mix them using a mixing matrix and then perform ICA to get the independent components.

#### Independent Sources:
![image](https://user-images.githubusercontent.com/97335445/226475736-9095dbc5-7b04-4e70-bab0-c69243ea2dd6.png)

#### Mixed Signals:
![image](https://user-images.githubusercontent.com/97335445/226475778-f103ecc8-900f-4451-9da8-33b056890d45.png)

#### Unmixed Signals:
![image](https://user-images.githubusercontent.com/97335445/226475912-bd99f84e-5547-42b7-8d27-7edb98be6974.png)
