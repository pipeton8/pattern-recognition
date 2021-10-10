# Assignment 2: Gender Recognition

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pipeton8/pattern-recognition/blob/main/assignments/2%20-%20Gender%20recognition/assignment2_fdc.ipynb)

## Description
The objective of this assignment is to design an automatic gender (male/female) recognizer using feature extraction (e.g., texture, geometry), feature selection and a KNN classifier. The database that is downloaded in the Colab Notebook contains 1400 images grayscale faces of 165x120 pixels. There are 700 images belonging to class 0 (male) and 700 images belonging to class 1 (female). Below are some examples of each class:

<table>
  <tr>
    <td align="center">Male</td>
    <td align="center">Female</td>
  </tr>
  <tr>
    <td style="center">
      <img src="https://github.com/pipeton8/pattern-recognition/blob/main/assignments/2%20-%20Gender%20recognition/arg_01.png" width="600">
    </td>
    <td>
      <img src="https://github.com/pipeton8/pattern-recognition/blob/main/assignments/2%20-%20Gender%20recognition/arg_02.png" width="600">
    </td>
  </tr>
</table>

The images are stored as `face_00x_nnnn.png`, where `x` equals 1 for males and 2 for females, and `nnnn` = 0001, 0002, ... 0700 indicates the image number. For training purposes, the first 630 images of each class should be used, while the remaining 70 are used for testing.

The classifier must work over a maximum of 12 features. For this, at least 200 features must be extracted and at most 12 will be selected using feature transformation or selection techniques. For example, an strategy that first extracts 1000 features, then selects 100 and transforms them (using PCA, PLSR, or others) into 12 that are fed to the classifier, is a valid approach. All combinations of transformation and selection are allowed. 

The only allowed classifier is a three-neighbor KNN classifier.

IT IS ALLOWED: 
- Use of features not seen in class (but not based on Deep Learning).
- Use of feature extraction libraries.
- KNN classifier libraries.
- Math functions libraries (e.g., covariance, matrix multiplication, vector operations).
- Feature normalization functions.
- Feature selection and transformation libraries.
- Evaluation libraries.
- Visualization libraries.

IT IS NOT ALLOWED:
- Use techniques based on Deep Learning.
- Use other classifiers different from KNN.
