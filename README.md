# Teeth_classification
Project Overview
This project focuses on classifying teeth images into different categories. It uses a CNN model for feature extraction and classification. The goal is to accurately predict the class of each image, representing a specific type of tooth.

Features:
Multi-class image classification
Data augmentation to improve model performance
Visualization of training and validation accuracy/loss
Exclusion of specific folders during testing
Dataset
The dataset consists of images of teeth, divided into different classes representing various types of teeth.

Training Directory: Teeth_Dataset/Training
Validation Directory: Teeth_Dataset/Validation
Testing Directory: Teeth_Dataset/Testing

Model Architecture
The model is built using the TensorFlow and Keras libraries. It includes:

Convolutional layers: For extracting features from the images
Pooling layers: For down-sampling
Fully connected layers: For classification
Regularization techniques: Dropout and batch normalization
The architecture is flexible and can be customized as per your needs
