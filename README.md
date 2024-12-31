# Face Mask Detection using CNN

## Overview

#### This project demonstrates a Face Mask Detection System using a Convolutional Neural Network (CNN). The model is trained to classify images into two categories:

- #### With Mask
- #### Without Mask
#### The system can analyze images and predict whether the subject is wearing a face mask based on the input data.

---

## **Features**

- #### Binary classification of images: With Mask or Without Mask.
- #### Simple CNN architecture for efficient training and inference.
- #### Trained on preprocessed datasets for optimal performance.

---

## Technologies Used

- #### Programming Language: Python
- #### Frameworks and Libraries:
  - ##### TensorFlow/Keras (for deep learning and model creation)
  - ##### NumPy, Pandas (for data manipulation)
  - ##### Matplotlib, Seaborn (for data visualization)

---

## Dataset

### The dataset consists of images in two categories:
- #### With Mask
- #### Without Mask
### Preprocessing steps:
- #### Images resized to a uniform size (e.g., 128x128 pixels).
- #### Pixel values normalized to a range of [0, 1].
- #### Dataset split into training, validation, and testing sets for model evaluation.

---

## Model Architecture

### The CNN model includes:

- #### Convolutional Layers: To extract image features like edges and textures.
- #### Pooling Layers: To reduce the size of feature maps while retaining key information.
- #### Dense Layers: Fully connected layers to classify images into two categories.
- #### Activation Function: ReLU for intermediate layers and Sigmoid for the output layer.
- #### Optimizer: Adam optimizer for efficient learning.
- #### Loss Function: Sparse Categorical Crossentropy for classification.
