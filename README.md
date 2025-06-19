# IMAGE-CLASSIFICATION-MODEL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DONTHIREDDY MAHIMA REDDY

*INTERN ID*:CT08DF57

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH

*TASK-3*

*DESCRIPTION*:

# Image Classification Model – CNN with TensorFlow

This project completes building a **Convolutional Neural Network (CNN)** using TensorFlow for image classification on the **CIFAR-10** dataset.

# Objective

To build a functional image classification model using CNN architecture in TensorFlow and evaluate its performance on a standard test dataset.

# Dataset: CIFAR-10

It consists of :
- 60,000 32×32 color images in 10 classes
- Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- Dataset is built-in via `tensorflow.keras.datasets.cifar10`

# Tools & Technologies

- Language: Python
- Framework: TensorFlow 2.x
- Libraries: Keras, Matplotlib

# Model Architecture

- 3 Convolutional layers with ReLU activation
- 2 MaxPooling layers for downsampling
- 1 Flatten layer
- 2 Dense layers (1 hidden + 1 output with softmax)

# Evaluation Results

- **Loss Function:** sparse categorical crossentropy
- **Optimizer:** Adam
- **Test Accuracy Achieved:** ~70–75% (varies per run)
- Visualized training vs. validation accuracy and loss


