# Implementation-of-PCA-ICA

Implementation of PCA (Principal Component Analysis) and ICA (Independent Component Analysis) from scratch.

### `PCA.ipynb` 
- Implements Principal Component Analysis from scratch on the MNIST Dataset. It converts each image into a 784-dimension vector. Since it is a 28 x 28 image, we get 784 pixels.
- I split the training dataset in a `80:20` ratio for training and testing respectively. I perform PCA on the training data and then use k-Nearest Neighbors to test the testing data.

### `ICA.ipynb`
- Implement Independent Component Analysis to mix 2 signals i.e. a sinusoidal wave and a ramp wave.
- I mix them using a mixing matrix and then perform ICA to get the independent components.

The mixing matrix:
$$
\begin{bmatrix}
0.5 & 1\\
1 & 0.5
\end{bmatrix}
$$
