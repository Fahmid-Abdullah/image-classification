# Image Classification with Convolutional Neural Networks

This repository contains code for a simple image classification task using Convolutional Neural Networks (CNNs) implemented in Python with TensorFlow and OpenCV.

## Overview

The goal of this project is to classify images into 10 different categories: planes, cars, birds, cats, deers, dogs, frogs, horses, ships, and trucks. We utilize the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 testing images.

## Dependencies

- Python 3.x
- TensorFlow
- OpenCV
- NumPy
- Matplotlib

You can install the required dependencies using pip:

```bash
pip install tensorflow opencv-python matplotlib
```

# Usage
1. Clone this repository:
```bash
git clone https://github.com/your_username/image_classification.git
cd image_classification
```

2. Run each section in the notebook image_classification.ipynb in order to train and evaluate the CNN model for image classification.

3. After training, the model will be saved as image_classification.keras. You can load this saved model for testing or further use.

4. Ensure that you have images of the classes you want to predict in a folder named Images. The images should be named after their classes, for example, Plane.jpg, Car.jpg, etc.

# Limitations
Due to time constraints, the training data has been limited to 20,000 samples, and the testing data to 4,000 samples. For better accuracy, you can remove these limitations and train the model on the entire dataset.


