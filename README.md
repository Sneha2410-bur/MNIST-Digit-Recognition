# MNIST-Digit-Recognition
Project Overview

This project implements a handwritten digit recognition system using the MNIST dataset. The dataset contains grayscale images of handwritten digits from 0 to 9, each with a resolution of 28 × 28 pixels.

Dataset

- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28 pixels
- Classes: 10 digits (0–9)

Methodology

1. Load the MNIST dataset.
2. Inspect the training and testing data.
3. Preprocess the images and normalize pixel values.
4. Build and compile a neural network.
5. Train the model on the training dataset.
6. Evaluate the model on the test dataset.
7. Display predicted digits and evaluate classification performance.
8. Save the trained model.

Model Configuration

- Input: 28 × 28 grayscale images
- Output: 10 digit classes
- Optimizer: See the model compilation cell in the notebook.
- Activation functions: See the model architecture in the notebook.
- Loss function: See the model compilation cell in the notebook.

Results

The model achieved a test accuracy of 97.20% in the reported evaluation.

Training accuracy and loss graphs, a confusion matrix, and sample predictions can be added to the "results/" folder.

How to Run

1. Open the notebook in Google Colab.
2. Upload or load the MNIST dataset as required by the notebook.
3. Run the cells in order, from data loading through evaluation.
4. View the test accuracy, predictions, and evaluation graphs.

Technologies

- Python
- NumPy
- Matplotlib
- TensorFlow / Keras

Future Improvements

- Add a confusion matrix and classification report.
- Compare different neural network architectures.
- Improve the model and analyze misclassified digits.
