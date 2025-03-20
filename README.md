# Building Own CNN Image Classifier

## Overview

This project focuses on leveraging transfer learning with a pre-trained Convolutional Neural Network (CNN) to build an image classifier for distinguishing between dogs and cats. By the end of this project, you will gain hands-on experience in:

- Using CNNs for image classification
- Implementing transfer learning with models like VGG, MobileNetV2, and ResNet
- Fine-tuning models for better accuracy
- Customizing data loading and augmentation techniques
- Tracking model performance using TensorBoard

## Files

The Folder consists of:

- 📂 **Jupyter Notebook (.ipynb)**  
  Contains Python code for building the classifier.  
 

- 📄 **Documentation (.docx)**  
  Stepwise explanation with screenshots.  
  

## Dataset
  Download the Dogs vs. Cats dataset from Kaggle: [Dataset Link](https://www.kaggle.com/c/dogs-vs-cats/data).  
  Extract the `train.zip` file to obtain 25,000 images of dogs and cats.  
  Split into training and testing sets for model development.

## 🚀 Steps for Implementation

### 📌 Data Preparation
- Split the dataset into training and test sets.
- Perform data preprocessing and augmentation.

### 🏗️ Model Development
- Utilize transfer learning with pre-trained models (VGG, MobileNetV2, ResNet).
- Train a classifier on top of the pre-trained model.
- Fine-tune the model to enhance performance.

### 🛠️ Custom Data Loader
- Implement a custom `ImageLoader` function for on-the-fly augmentations.
- Specify at least 3-4 augmentation techniques.

### 📊 Model Training & Evaluation
- Train models using Google Colab or a personal computer.
- Track performance using TensorBoard (bonus points for visualization).
- Justify chosen hyperparameters in the Jupyter Notebook.
