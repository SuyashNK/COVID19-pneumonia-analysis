# COVID19-pneumonia-analysis



## Introduction

Welcome to the `GokulSirHDA.ipynb` Colaboratory notebook! This notebook is designed for image classification tasks related to the Covid19-dataset. It leverages Convolutional Neural Networks (CNNs) implemented using the Keras library to classify images into three categories: 'Covid,' 'Normal,' and 'Viral Pneumonia.'

## Overview

### Dataset Preparation

The notebook begins by loading and preprocessing the dataset stored in the directories:

- Training directory: `/content/drive/MyDrive/data/HDA/Covid19-dataset/train`
- Testing directory: `/content/drive/MyDrive/data/HDA/Covid19-dataset/test`

Images are resized to 500x500 pixels, normalized, and categorized. The labels are encoded for training and testing data.

### Model Architecture

The CNN model consists of convolutional layers, max-pooling layers, flattening layers, and fully connected layers. The architecture is as follows:

1. Input Layer: 500x500 pixels with 3 channels
2. Convolutional Layers with ReLU Activation
3. Max Pooling Layers
4. Flatten Layer
5. Dense Layers with ReLU Activation and Dropout
6. Output Layer with Softmax Activation (3 classes)

### Training

The model is trained using the Adam optimizer with a categorical crossentropy loss function. The training process is executed for 10 epochs, and the progress is visualized with accuracy metrics.

## Training Results

The training results indicate the model's performance on both training and validation sets:

- Training Accuracy: 88.67%
- Validation Accuracy: 75.00%

## Usage

To run the notebook:

1. Upload the notebook (`GokulSirHDA.ipynb`) to your Colaboratory environment.
2. Ensure the required libraries are installed.
3. Execute each cell in sequence.

Feel free to explore, modify, and adapt the notebook for your specific image classification tasks. If you encounter any issues or have questions, don't hesitate to reach out.

---

*Note: Adjust paths and parameters based on your dataset and requirements.*
