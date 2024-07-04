# Brain-Tumor-Detection
This repository contains code for detecting brain tumors from MRI images using a Convolutional Neural Network (CNN). The dataset used for this project is sourced from Kaggle:

## Setting Up the Environment

To set up this project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone (https://github.com/Diksha1312/Brain-Tumor-Detection
   cd Brain-Tumor-Detection


2. **Create and Activate Conda Environment**

   ```bash
   conda create -n env python=3.6
   conda activate env

3. **Install Requirements**

   ```bash
   pip install -r requirements.txt

4. **Pytorch Installation**

   Additionally, PyTorch should be downloaded from the official PyTorch website (pytorch.org) based on your system requirements to ensure compatibility and proper functioning.

## Project Overview

### Usage

After setting up the environment, you can run the code to train and evaluate the model. The steps involve normalizing the dataset, splitting the dataset, creating DataLoaders, defining the model, training the model, and evaluating the model.

### Summary

This project focuses on detecting brain tumors from MRI images using a Convolutional Neural Network (CNN). The dataset, sourced from Kaggle, consists of MRI images classified into two categories: Tumor and Healthy. The images are preprocessed by resizing them to 128x128 pixels and normalizing their pixel values to the range [0, 1]. A custom PyTorch Dataset class is created to manage image loading and preprocessing, and DataLoaders are used for efficient batching and shuffling of the dataset. The CNN model, built using PyTorch, includes convolutional and fully connected layers to learn and classify the images. The model is trained using the Adam optimizer and Binary Cross-Entropy Loss, with periodic loss printing for progress monitoring. After training, the model's performance is evaluated on a validation set, and metrics such as accuracy and confusion matrix are computed to assess its effectiveness. The setup instructions include environment creation and package installation steps to ensure the code runs smoothly.
