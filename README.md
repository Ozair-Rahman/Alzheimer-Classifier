# Alzheimer Classifier
## Introduction
The goal of this model is to classify brain MRI images into 4 categories,  Non Demented, Very Mild Demented, , Mild Demented and Moderate Demented.
## Dataset
The dataset was found on Kaggle and is linked below:
https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images
## Libraries
The following libraries were used to create the model:

<b>Tensorflow</b>

Used to import dataset, perform data augmentation, create model and make predictions

<b>Matplotlib</b>

Used for data visualization

<b>Numpy</b>

Used to help make prediction

<b>OpenCV</b>

Used to import images for predictions

## Note
- The Images located outside of the directories (Non_Demented_Test, Very_Mild_Demented_Test, Mild_Demented, and Modern_Demented) are there for testing purposes in order to be used as testing data. The images were pulled from the validation section of the dataset.
- The Saved Models directory contains multiple models showing the progress of training the model. Use model_6.h5 for the most up to date model that is best trained.