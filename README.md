# SVM Classifier for Dog and Cat Images

This project implements a Support Vector Machine (SVM) classifier to distinguish between images of dogs and cats. The goal is to train a model that can accurately classify new images as either a dog or a cat. The project uses a Kaggle dataset and is designed to run in Google Colab.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Training](#training)


## Introduction

Image classification is a fundamental task in computer vision. This project aims to classify images of dogs and cats using a Support Vector Machine (SVM), a powerful supervised learning algorithm that is effective in high-dimensional spaces.

## Dataset
The dataset used in this project is sourced from Kaggle. You can download it from the following link:

https://www.kaggle.com/c/dogs-vs-cats/data

## Preprocessing
Before training the SVM classifier, the data needs to be preprocessed. This includes:

- Resizing images to a consistent size
- Converting images to grayscale or RGB
- Normalizing pixel values
- Splitting the data into training and testing sets

## Training
The SVM classifier is trained using the preprocessed images. The training process is implemented in the file. Key steps include:

- Loading and preprocessing the dataset
- Extracting features from the images
- Training the SVM model
- Saving the trained model
