# part-2-cnn-computer-vision
computer-vision
# CNN-Based Manufacturing Defect Classification

## Project Overview

This project focuses on building a Convolutional Neural Network (CNN) model for manufacturing defect classification using computer vision techniques.

The CNN model classifies product images into four categories:

* normal
* scratch
* dent
* stain

The project demonstrates how deep learning and computer vision can be applied in automated industrial quality inspection systems.

---

# Problem Type

The dataset represents an Image Classification problem because each image belongs to one predefined defect category.

---

# Dataset Information

Dataset Classes:

* normal
* scratch
* dent
* stain

Tasks performed:

* Dataset exploration
* Image preprocessing
* CNN model creation
* Model training and evaluation
* Confusion matrix generation
* Sample prediction visualization

---

# Image Preprocessing

The preprocessing pipeline includes:

* Image resizing
* Pixel normalization
* Train-test splitting
* Data augmentation

---

# CNN Architecture

The CNN model includes:

* Convolution layers
* ReLU activation
* MaxPooling layers
* Flatten layer
* Dense hidden layer
* Softmax output layer

---

# Evaluation Metrics

The model evaluation includes:

* Training accuracy
* Validation accuracy
* Testing accuracy
* Loss analysis
* Confusion matrix
* Sample predictions

---

# CNN Concepts

## What is Convolution?

Convolution uses filters to detect image features such as edges, textures, scratches, and dents.

## Why is Pooling Used?

Pooling reduces image size and computational complexity while preserving important features.

## Why is ReLU Used?

ReLU introduces non-linearity and improves CNN training efficiency.

## Why are CNNs Better for Images?

CNNs preserve spatial image information and automatically learn visual patterns better than regular neural networks.

---

# Business Use Case

This CNN-based solution can be used in manufacturing industries for automated defect detection and quality inspection.

Benefits:

* Faster inspection
* Reduced human error
* Improved product quality
* Industrial automation support

---

# Technologies Used

* Python
* TensorFlow/Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

# Project Structure

```text id="v7xkqz"
part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
├── sample_predictions/
│   └── prediction_outputs.png
└── results/
    ├── accuracy_loss_curves.png
    └── confusion_matrix.png
```

---

# How to Run

Install dependencies:

```bash id="gbm5w7"
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash id="x6o0we"
jupyter notebook
```

Run:

```bash id="8xlyfw"
notebook.ipynb
```
