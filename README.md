# Handwritten-Digit-Recognition

## Overview

Handwritten Digit Recognition is a deep learning project that involves the recognition and classification of handwritten digits into numbers between 0 and 9. This project is built upon a deep learning model trained on the `MNIST` dataset, a widely used dataset for digit recognition tasks. Additionally, a simple user interface has been implemented using the `Pygame` module to provide a user-friendly experience.

## Technolgies/Modules used

- `Keras`: Keras is a high-level neural networks API written in Python. It is widely used for building and training deep learning models due to its simplicity and flexibility.
- `Pygame`: Pygame is a popular cross-platform set of Python modules designed for writing video games. In this project, Pygame is used to create a graphical user interface for interacting with the digit recognition model.

## Dataset

The dataset used for training and testing the digit recognition model is the `MNIST` dataset. MNIST is a collection of 28x28 pixel grayscale images of handwritten digits, ranging from 0 to 9. It is a benchmark dataset for machine learning and computer vision tasks, making it an ideal choice for this project.

## How it works

1. **Data Preprocessing**: The MNIST dataset is preprocessed to normalize the pixel values and prepare it for training.

2. **Deep Learning Model**: A deep learning model, typically a Convolutional Neural Network (CNN), is constructed using the Keras framework. This model is trained on the preprocessed MNIST dataset to learn the patterns and features of handwritten digits.

3. **User Interface**: The Pygame module is used to create a simple user interface that allows users to draw a digit on the screen using a mouse or touch input.

4. **Digit Recognition**: When the user submits the drawn digit, the model processes the image of the digit and predicts the corresponding number between 0 and 9.

5. **Display Result**: The predicted digit is displayed on the screen, providing instant feedback to the user.

## Getting Started

To run this project on your local machine, follow these steps:

1. Fork the repository
2. Clone the repository to your local machine <br>`git clone https://github.com/your-username/handwritten-digit-recognition.git`
   <br>
   Replace `your-username` with your GitHub username
3. Install the required Python libraries and dependencies:
   <br>
   `pip install keras pygame`
   <br>
4. Go to the location where your file is stored and run using command prompt:
   <br>
   `python main.py`

## Contributors

Suhas P Shroff

## Acknowledgments

- MNIST Dataset
- PyGame Documentation
- Keras Documentation
- CampusX
