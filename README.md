Driver Drowsiness Detection

 Project Overview

This project is designed to detect driver drowsiness using advanced deep learning techniques. It leverages Transfer Learning with InceptionResNetV2 and a custom CNN architecture featuring Parallel Convolution layers to achieve high performance.

 Dataset

Source: Driver Drowsiness Dataset (DDD)

Categories: Drowsy and Non-Drowsy images

Purpose: Train and evaluate model performance

 Setup and Requirements

Ensure the following libraries are installed:

pip install tensorflow pandas matplotlib seaborn opencv-python pillow

 Data Pipeline

1️ Data Preparation

Organized dataset: Drowsy and Non-Drowsy categories

Dataframes: Manage file paths and labels

Visualization: Count plot to inspect category balance

2️ Data Augmentation and Splitting

Augmentation: Rotation, zoom, shear (via ImageDataGenerator)

Split: Training, Validation, Test sets using train_test_split

 Model Architecture

🔹 Transfer Learning Model

Uses InceptionResNetV2 pretrained weights

Fine-tuned on the Driver Drowsiness Dataset

🔹 Custom Parallel CNN

Built from scratch

Parallel Convolution layers to capture diverse features

✅ Optimizer: Adamax
✅ Loss Function: Categorical Crossentropy

 Training and Evaluation

🔸 Training

Trained over multiple epochs

Plots: Accuracy and Loss trends for training and validation

🔸 Evaluation

Performance: Tested on training, validation, and test datasets

Reports: Classification report + Confusion matrix

🔸 Prediction and Visualization

Sample predictions: Showcases model inference

Interpretability: Activation maps + Grad-CAM visualizations

 Results

Model

Accuracy

Transfer Learning

99.73%

Custom CNN

99.90%



This project showcases how deep learning models can effectively improve road safety by detecting driver drowsiness with impressive accuracy. The combination of Transfer Learning and a custom Parallel CNN architecture offers both performance and interpretability.

🚘 Drive Safe. Stay Awake. Stay Alive!

