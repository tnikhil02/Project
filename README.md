# Traffic Sign Detection using Deep Learning

## Project Overview
This project focuses on building a traffic sign detection model using deep learning techniques, specifically Convolutional Neural Networks (CNN) and Transfer Learning.

The goal of this project is to accurately detect and classify traffic signs in images, which can be useful in real-time applications like autonomous driving systems.

## Dataset
The dataset used for this project is sourced from Kaggle and contains 58 different classes of traffic signs. The classes include:
- Speed Limits (30, 40, 50, etc.)
- Turn directions (Go Left, Go Right, etc.)
- Miscellaneous signs (Go Straight, No Entry, Stop)

Each class is imbalanced, with varying amounts of data per class, making the project challenging from a data distribution perspective.

## Techniques Used
### Convolutional Neural Networks (CNN)
CNNs are well-suited for image recognition tasks, and in this project, they are used to extract features from the traffic sign images.

### Transfer Learning
Transfer Learning is employed to leverage a pre-trained model to improve performance, especially given the class imbalance in the dataset. Fine-tuning a model pre-trained on a large dataset (like ImageNet) helps achieve better accuracy with limited data for certain classes.

## Model Architecture
The model consists of:
- Convolutional layers for feature extraction
- Fully connected layers for classification
- Batch normalization and dropout for regularization and preventing overfitting
