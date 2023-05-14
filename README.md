# Diabetic Retinopathy Detection using CNN on Jetson Nano
This is a project for detecting diabetic retinopathy using Convolutional Neural Networks (CNN) and implemented on Jetson Nano.

# Dataset
The dataset used for this project is the https://www.kaggle.com/c/diabetic-retinopathy-detection from Kaggle. The dataset contains retinal images that were graded for diabetic retinopathy on a scale of 0 to 4, where 0 indicates no diabetic retinopathy and 4 indicates the presence of severe diabetic retinopathy.

# Requirements
To run this project, you will need the following:

* Python 3
* Tensorflow 2
* Keras
* OpenCV
* Jetson Nano

# Usage
1. Download the https://www.kaggle.com/c/diabetic-retinopathy-detection dataset from Kaggle and extract it to the dataset folder.
2. Import the required libraries.
3. Visualize and clean the dataset.
4. Pre-process the dataset using Ben Graham Pre-Processing technique.
5. The dr-cnn-model(1).h5 file have the weights of a trained model using CNN. This file can be used to load the model.
6. Now, the loaded model can predict on the test dataset.

# Performance
The model achieves an accuracy of 94% on the test set.

# Credits
This project was created by Vidhi Patel.
