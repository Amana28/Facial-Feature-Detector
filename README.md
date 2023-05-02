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

# Running the code
The code consists of the following files:

- Upload the celebA dataset to your google drive as a zip file
- Upload all companion files to the celebA images dataset
- Set the right paths for the corresponding files  
- Run the notebook porvided 

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
