# Semi-Supervised Deep Learning with GANs for Melanoma Detection

## Background
Working through the training course [Semi-Supervised Deep Learning with GANs for Melanoma Detection](https://www.manning.com/liveproject/semi-supervised-deep-learning-with-gans-for-melanoma-detection)

- Setup an image pre-processing pipeline that handles data augmentation and prepares your data to be fed as input to a Pytorch model.
- Train a fully supervised melanoma classifier on the labeled data that you have, and test it to serve as a baseline.
- Train a semi-supervised GAN model to make use of the unlabeled training data. Run the trained model on the test set and compare its performance to the supervised baseline.

## Contents
- [Solving MNIST with Pytorch](0_mnist.ipynb) 

## Dataset
- The MelanomaDetection folder contains the image dataset separated into three folders: labeled, unlabeled and test
- The images are a pre-processed subset of a dataset available through the Dataverse project.
- All images are color 32x32 pixel JPG files.
- The naming convention for images in the labeled and test folders is as follows: each filename ends with either *_0.jpg or *_1.jpg, corresponding to a melanoma-negative or melanoma-positive image respectively.
- Number of files
    - Labeled: 200 (evenly split between melanoma positive and negative)
    - Test: 600 (also evenly split between melanoma positive and negative)
    - Unlabeled: 7018 (class distribution unknown)