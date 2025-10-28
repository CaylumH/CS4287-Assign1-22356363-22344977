# CS4287-Assign1-CNNs

Open Data Repositories Used

MNIST Handwritten Digit Database
Source: http://yann.lecun.com/exdb/mnist/
Accessed via TensorFlow

MNIST - Dataset of images with handritten numbers from 0 to 9 on each one

Each image is 28 by 28 pixels and in black and white

AlexNet - CNN that recognises features in images

AlexNet made up of layers:
Input layer: Takes in image
Convolution layers: Find simple patterns like lines or edges
Pooling Layers: downsizes image, keeping most important info (increases efficiency and can prevent overfitting)
Fully connected layers: combine all layers to make decision
Output layer: Gives decision like "number 8"

We need to apply AlexNet to the MNIST dataset

AlexNet was originally made for the Dataset ImageNet, which takes images of 224 x 224 pixels in RGB (full colour), so we need to adapt AlexNet to work on MNIST 