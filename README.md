# Facial Features Detection with Convolutional Neural Networks

This repository contains code for training a Convolutional Neural Network (CNN) on the CelebA dataset to detect facial features such as eyes, nose, and mouth. Currently we are focusing on predicting the attractiveness of faces to tune our model but plan to predict more than 10 attributes in the future. 

# Dataset
The CelebA dataset contains over 200,000 celebrity images with annotations for various facial features. For this project, we will use a subset of the dataset (50000 images) which has been preprocessed and contains 64x64 pixel images.

# Prerequisites
To run this code, you will need the following libraries:

- TensorFlow (version 2.0 or later)
- NumPy
- Pandas
- Matplotlib
You can install these libraries using pip:

# Downloading the dataset
The code consists of the following files:

## img_align_celeba.zip
- You can download this zip file by going to this link (https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
- Click on the Google Drive link -> Img and you should find it there (You can also use Baidu link provided)

## list_attr_celeba.txt
_ You can dowload this file from the save google drive link as the above file
- Google Drive link -> Anno

# Results
Our trained model achieved a validation accuracy of 78%. While this is a decent result, there is certainly room for improvement. Some possible avenues for improving the model include:

- Using a larger CNN architecture with more layers and parameters
- Increasing the size of the input images beyond 64x64 pixels
- Use a larger portion of the dataset
- Tuning hyperparameters such as the learning rate, batch size, and number of epochs

# Extensions

- Being able to predict more than one attribute with high accuracy 

## Contributed by
- Amanuel Tesfaye
- Wasay Qureshi
