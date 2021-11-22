# Assignment 3: Skin Lesion Classifier

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pipeton8/pattern-recognition/blob/main/assignments/3%20-%20Skin%20lesion%20classifier/assignment3_fdc.ipynb)

## Description
The objective of this assignment is to design an automatic cancer mole classifier based on mole pictures. For this task, the images belong to the database of  the [International Skin Imaging Collaboration](https://coh.centre.uq.edu.au/project/international-skin-imaging-collaboration), that implemented the Melanoma Project. This project "is an international academia and industry partnership designed to develop and promote standards for digital skin imaging to help reduce melanoma mortality". 

The database contains 3600 color images of 600x450 pixels, each belonging to one two classes (0: benign, 1: malignant). The image distribution is as follows:
* Training: 2700 images (1350 images per class)
* Validation: 300 images (150 iamges per class)
* Testing: 600 images (300 images per class)

Some example images are show below

<img src="https://github.com/pipeton8/pattern-recognition/blob/main/assignments/3%20-%20Skin%20lesion%20classifier/example.png" width="800">

The images are divided in three directories: `train`, `val` y `test`, and each one of these is at the same time divided into two sub-directories: `class_0` y `class_1`, that store the images for each class.

In this assignment, the classifier must be able to discrimate correctly between the two classes. For this, a three "block" strategy must be designed:
1. Feature extraction.
2. Feature normalization, selection and/or transformation.
3. Classification.

Moreover, in the assignment must be compared at least 5 different strategies. Two strategies are different if they differ in at least two of their "blocks". Every parameter and hyperparameter of the model can be adjusted using the validation set. The solution must be evaluated on the testing set. 

IT IS ALLOWED:
- use of feature extraction, selection and transformation libraries (e.g., `pybalu`).
- use of classifier libraries (e.g., `scikit-learn`).
- use of math function libraries (e.g., `numpy`)
- use of visualization libraries (e.g., `seaborn`, `matplotlib`)

IT IS NOT ALLOWED:
- use of deep learning techniques, nor neural networks of two or more hidden layers.
