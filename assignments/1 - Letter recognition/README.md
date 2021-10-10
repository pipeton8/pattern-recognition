# Assignment 1: Letter Recognition

* Assignment [[link]](https://github.com/pipeton8/6.864-advanced-nlp/blob/main/Assignments/Assignment%202/Assignment%202.pdf)
* Colab notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pipeton8/pattern-recognition/blob/main/Tarea1_FdC_Patrones.ipynb)

## Description
The objective of this assignment is to design and evaluate a classifier for letters X, Y, Z, A, B, in different fonts. In the zip file that is downloaded in the Colab Notebook there are 100 images for each one of the five letters. Some of them are shown below:

<img src="https://github.com/pipeton8/pattern-recognition/blob/main/samples.png" width="600">

The image are stored as `'char_nn_kkk.png'`, where nn = 01, ... 05, indicates the coded letter class (X, Y, Z, A, B respectively), and kkk = 001, 002, ... 100 indicates the image number.

In this assignment, there is freedom to extract as many features as needed in order to design the classifier. The classifier should be trained using 75 pictures of each class and tested on the remaining 25. However, there are certain restrictions:
  * Only image processing functions whose input and output are images are allowed.
  * Is not allowed to use functions that extract image features directly.
  * Is not allowed to use functions that classify.
  * Is not allowed to use functions that perform evaluationn.
