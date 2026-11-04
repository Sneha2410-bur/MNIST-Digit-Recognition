# MNIST-Digit-Recognition
1.Project Overview
This project focuses on recognizing handwritten digits (0–9) using a Convolutional Neural Network (CNN).
The project was upgraded from an Artificial Neural Network (ANN) to a CNN to improve image feature extraction and classification.

2.Dataset
 Dataset: MNIST
 Image dimensions: 28 × 28 pixels
 Number of classes: 10 (0–9)
 Training images: 60,000
 Testing images: 10,000

3.Data Preprocessing
 Pixel normalization (0–1)
 Image reshaping
 Dataset preparation for CNN

4.CNN Architecture
 Conv2D
 MaxPooling2D
 Conv2D
 MaxPooling2D
 Flatten
 Dense
 Dropout
 Output layer (10 classes)

5.Optimizer
AdamW optimizer with:
 Learning rate: 0.001
 Weight decay: 0.0001

6.Combined Loss Function
Combined loss consisting of:
 Sparse Categorical Crossentropy
 Mean Squared Error (if used in the final implementation)

7.Model Training
- Epochs: 50
- Batch size: 128
- Validation split: 10%

8.Model Evaluation
Evaluation using:
 Test accuracy
 Test loss
 Precision
 Recall
 F1-score

9. Visualizations
 Training vs Validation Accuracy
 Training vs Validation Loss
 Confusion Matrix

10.Technologies Used
 Python
 TensorFlow / Keras
 NumPy
 Matplotlib
 Seaborn
 Scikit-learn
 Google Colab

11.Conclusion
The project demonstrates handwritten digit classification using CNN with AdamW optimization and combined loss.
Further experiments can compare different optimizers and model configurations.
