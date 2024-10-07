# Traffic Signs Classification using Convolutional Neural Networks

## Project Overview
This project aims to classify traffic signs using Convolutional Neural Networks (CNNs) in TensorFlow and Keras. By training on a dataset of German traffic sign images, the project develops models capable of recognizing various traffic signs, facilitating advancements in automated driving systems and traffic management.

## Technologies Used
- **TensorFlow**: For building and training the neural network models.
- **Keras**: High-level neural networks API, used for fast experimentation.
- **Python**: Primary programming language.
- **Matplotlib**: For visualizing the training results and image samples.

## Dataset
The dataset used is the [German Traffic Sign Recognition Benchmark (GTSRB)](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign), which contains thousands of images of traffic signs across multiple classes, making it one of the most comprehensive traffic sign datasets available.

## Model Description
The project employs three different CNN architectures to explore their effectiveness in image classification tasks. Each model's architecture is tailored to process and classify images based on their unique features efficiently:
- Model 1: Basic CNN with two convolutional layers.
- Model 2: Intermediate CNN with additional convolutional layers and dropout for regularization.
- Model 3: Advanced CNN with deeper layers to capture more complex patterns.
