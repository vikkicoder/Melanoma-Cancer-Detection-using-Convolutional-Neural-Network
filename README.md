# Melanoma Cancer Detection using Convolutional Neural Network
by 

Vishnu Vardhan Gudla

## Problem Statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Data: Dataset can be downloaded from here https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Table of Contents
* Project Pipeline
* Importing Skin Cancer Data
* Visualize the Data
* Create, compile & train the Model
* Create, compile & train the Model on Augmented data
* Rectify the Class Imbalance using Augmentor package
* Create, compile & train the final Model 
* Analysis on Test Data
* Conclusions

## Technologies Used
* TensorFlow
* keras
* NumPy 
* Pandas
* Augmentor



## Conclusions
- There is class Imbalance in image data provided, used Augmentor package to rectify the issue
- Accuracy is good on Train and Validation sets
- Accuracy is bad on Test set
- Hence, there is chance of overfitting, more input data is required, more layers with Batch Normalization should be included.

