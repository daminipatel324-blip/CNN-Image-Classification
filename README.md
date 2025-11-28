📘 Image Classification using CNN (CIFAR-10)
📌 Project Overview

This project is a simple Convolutional Neural Network (CNN) built to classify images from the CIFAR-10 dataset into 10 categories such as airplane, automobile, bird, cat, dog, etc.

I created this project to strengthen my understanding of deep learning and to build a solid portfolio project for AI/ML roles.

🧰 Technologies Used

Python
TensorFlow / Keras
NumPy
Matplotlib
Google Colab

📂 Dataset: CIFAR-10

CIFAR-10 contains:
60,000 images
32×32 color images
10 classes
50,000 training images
10,000 testing images
This dataset is commonly used for benchmarking image classification models.

🏗️ Model Architecture

The CNN model includes:
Conv2D layers for feature extraction
MaxPooling layers to reduce spatial size
Flatten layer to convert 2D maps into vectors
Dense layers for classification
Softmax output layer for 10-class prediction

Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Metrics: Accuracy

🚀 Training Results

The model was trained for 5 epochs and achieved:

✅ Test Accuracy: ~70%

This is a strong baseline accuracy for a simple CNN on CIFAR-10.

🧪 Steps Performed

Imported required libraries
Loaded CIFAR-10 dataset
Normalized pixel values
Displayed sample training images
Built CNN model architecture
Compiled and trained the model
Evaluated test accuracy
Uploaded project to GitHub

🎯 What I Learned

Understanding of CNN layers
Image preprocessing & normalization
Model training and evaluation
Using Google Colab for GPU-based training
Saving and organizing ML projects on GitHub

🔧 Possible Improvements

Add Data Augmentation
Add Batch Normalization
Add Dropout
Increase epochs
Experiment with deeper architectures
These changes can push accuracy above 75–85%.

## 📊 Model Version Comparison

| Version | Description | Accuracy |
|--------|-------------|----------|
| **V1 – Basic CNN** | Simple CNN with 3 Conv layers | **70%** |
| **V2 – Improved CNN** | Added Data Augmentation, Batch Normalization, Dropout, and deeper Conv layers | **78%** |


👨‍💻 Author

DAMINIBAHEN PURANI
Master’s in Artificial Intelligence
Email: daminipatel324@gmail.com
GitHub: daminipatel324-blip
