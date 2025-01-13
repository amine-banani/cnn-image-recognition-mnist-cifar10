# cnn-image-recognition-mnist-cifar10

This project demonstrates the use of Convolutional Neural Networks (CNNs) for image classification tasks on the MNIST and CIFAR-10 datasets. Different CNN architectures and hyperparameters were explored to optimize model performance. The results, feature maps, and training/validation metrics are visualized to provide insights into the models' behavior.

---

## Overview

The project involves:  
1. Training CNN models on two widely-used datasets: MNIST (handwritten digits) and CIFAR-10 (colored images of 10 classes).  
2. Comparing different architectures and hyperparameters.  
3. Visualizing feature maps, training/validation accuracy, and error rates.

---

## Datasets

### **MNIST Dataset**  
- Grayscale images of size 28x28.  
- 10 classes representing digits from 0 to 9.  
- Achieved:
  - **Training Accuracy**: 99.58%.  
  - **Validation Accuracy**: 99.00%.

### **CIFAR-10 Dataset**  
- RGB images of size 32x32.  
- 10 classes, including airplanes, cars, birds, cats, etc.  
- Preprocessing steps:  
  - Loading and concatenating batch files into a single dataset.  
  - Reshaping images to (32, 32, 3) with channels-last format.  
  - Splitting a 5000-sample validation set from the training data.  
  - Normalizing pixel values to a range of [0, 1].  
- Achieved:
  - **Training Accuracy**: 78.23%.  
  - **Validation Accuracy**: 75.45%.

---

## Features

- Implemented CNN models with:
  - Varying architectures.
  - Different parameter combinations (e.g., kernel size, number of filters, strides).  
- Visualized:
  - Feature maps for insights into learned features.
  - Training and validation accuracy/error plots for performance tracking.  

---

## Results

### MNIST  
- **Training Accuracy**: 99.58%.  
- **Validation Accuracy**: 99.00%.  

### CIFAR-10  
- **Training Accuracy**: 78.23%.  
- **Validation Accuracy**: 75.45%.

---

## Tech Stack

- Python  
- Jupyter Notebook  
- TensorFlow / Keras  
- Matplotlib / Seaborn for visualization  
