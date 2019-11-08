# MNIST HAND-WRITTEN DIGIT CLASSIFICATION
## Dataset
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.
The MNIST database of handwritten digits, has a training set of 60,000 28x28 grayscale images of the 10 digits, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.<br/>
Sample images from MNIST test dataset:<br/>
![github-small](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)
## Image classification CNN model on MNIST dataset
The model consists of 2 convolutional layers which are followed by maxpooling layer. The output is fed to a dropout layer and then flattened. This is fed to a Dense layer which is followed by another Dense layer.
## Score
**Training Accuracy -** 99.19</br>
**Testing Accuracy -** 99.09

