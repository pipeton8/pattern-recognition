# Assignment 1: Letter Recognition

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pipeton8/pattern-recognition/blob/main/assignments/1%20-%20Letter%20recognition/assignment1.ipynb)

## Description
The objective of this assignment is to design and evaluate a classifier that is able to recognize letters X, Y, Z, A, B, in different fonts. In the zip file that is downloaded in the Colab Notebook there are 100 images for each one of the five letters. Some of them are shown below:

<img src="https://github.com/pipeton8/pattern-recognition/blob/main/assignments/1%20-%20Letter%20recognition/samples.png" width="600">

The images are stored as `char_nn_kkk.png`, where `nn` = 01, ... 05, indicates the coded letter class (X, Y, Z, A, B respectively), and `kkk` = 001, 002, ... 100 indicates the image number.

In this assignment, there is freedom to extract as many features as needed in order to design the classifier. The classifier should be trained using 75 pictures of each class and tested on the remaining 25.

IT IS ALLOWED:
  * use of image processing functions whose input and output are images.

IT IS NOT ALLOWED:
  * use of image processing functions whose input or output are not images (e.g., iamge feature extraction functions).
  * use external functions that extract image features directly.
  * use external functions that classify.
  * use external functions that perform evaluation.
