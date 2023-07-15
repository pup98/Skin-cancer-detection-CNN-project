# Skin-cancer-detection-CNN-project

Build a CNN-based model that detects melanoma. A data set will be downloaded from here!

## Problem Statement :
Design a multiclass classification model using a custom convolutional neural network in TensorFlow that can accurately detect melanoma. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma can potentially reduce a lot of manual effort needed in diagnosis.

## Documentation
The data set consists of 2,357 images of malignant and benign tumours, which were identified by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification by ISIC, and all subsets were divided into the same number of images, except for melanomas and moles, whose images are slightly dominant.

The data set contains images relating to the following diseases:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion
* Project Pipeline
* Following are all the steps to consider while working on the data set and subsequently the model:

## Workflow
* Data reading/data understanding: Define the path for training and testing images.
* Data set creation: Create, train and validate the data set from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
* Data set visualisation: Create code to visualise one instance of all the nine classes present in the data set.
* Model building and training: Create a model and report the findings. You can follow the below-mentioned steps:
* Create a CNN model that can accurately detect nine classes present in the data set. While building the model, rescale images to normalise pixel values between (0,1).
* Choose an appropriate optimiser and a loss function for model training.
* Train the model for epochs that can range from 5 to 20 depending upon your machine.
* Resolving underfitting/overfitting issues: Choose an appropriate data augmentation strategy to resolve model underfitting/overfitting.
* Model building and training on the augmented data: Follow the below-mentioned steps for building and training the model on augmented data:
* Create a CNN model that can accurately detect nine classes present in the data set. While building the model, rescale images to normalise pixel values between (0,1).
* Choose an appropriate optimiser and a loss function for model training.
* Class distribution: Examine the current class distribution in the training data set and explain the following:
* Handling class imbalances: Rectify class imbalances present in the training data set with the augmentor library.
* Model building and training on the rectified class imbalance data: Follow the below-mentioned steps for building and training the model on the rectified class imbalance data
* Create a CNN model that can accurately detect nine classes present in the data set. While building the model, rescale images to normalise pixel values between (0,1).
* Choose an appropriate optimiser and a loss function for model training.
* Build a confusion matrix. 
