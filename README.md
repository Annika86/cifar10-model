# CIFAR10-model

Goal of this learn project is to design, train and test a Convolutional Neuronal Network (CNN) model on the CIFAR-10 dataset.

## Background

The CIFAR-10 dataset consists of **60,000 color images in 32x32 pixel format**, divided into **10 classes**, with each class containing 6,000 images.
50.000 of these images are for training and 10.000 for testing.

These classes are:
* airplane
* automobile
* bird
* cat
* deer
* dog
* frog
* horse
* ship
* truck.

Each class has exactly the same number of images, meaning that the CIFAR-10 dataset can generally be considered as balanced.

This balanced distribution ensures that the model is trained evenly across different classes and not influenced by the frequency of certain classes.

Therefore, **random sampling** can be used for the train-validation-test split.

## Plan

How to proceed: (WIP)

- [x] load training and test data from the CIFAR10 dataset and split into 80% training and 20% validation data
- [x] add data loader
- [x] show first 10 train images with matplotlib to get an idea about the images
- [x] decide on an architecture
- [x] visualize the model with netron.app
- [x] implement architecture
- [x] implement loss function
- [ ] train the model
- [ ] test the model
- [ ] save
