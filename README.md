# 🧠 Handwritten Digit Recognition Using Deep Learning (MNIST)

## 📌 Project Overview

This project focuses on developing a Handwritten Digit Recognition System using Deep Learning techniques and the MNIST dataset.

The main objective is to recognize handwritten digits (0–9) from grayscale images by implementing and comparing three different neural network models:

- Perceptron
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

The project evaluates model performance and identifies which architecture provides the best prediction accuracy.

## 🎯 Project Objectives

- Understand the fundamentals of Deep Learning.
- Perform data preprocessing and normalization.
- Implement different neural network architectures.
- Train and evaluate deep learning models.
- Compare model performance using accuracy and loss.
- Visualize predictions and evaluation results.

## 🛠️ Technologies & Libraries Used

| Technology   | Purpose                       |
| ------------ | ----------------------------- |
| Python 🐍    | Programming language          |
| NumPy        | Numerical computations        |
| Pandas       | Data manipulation             |
| Matplotlib   | Data visualization            |
| Seaborn      | Statistical visualization     |
| TensorFlow   | Deep Learning framework       |
| Keras        | Neural network implementation |
| Scikit-learn | Model evaluation              |

## 📂 Dataset Description

Dataset: MNIST Handwritten Digits Dataset

- Training dataset: 59,999 records
- Testing dataset: 9,999 records
- Image dimensions: 28 × 28 pixels
- Total features: 784 pixel values
- Output classes: 0 to 9
- Image type: Grayscale

Each image contains 784 pixel values representing a handwritten digit.

## ⚙️ Project Workflow

1\. Dataset Collection

Load MNIST training and testing datasets

2\. Data Preprocessing

Cleaning, normalization and reshaping

3\. Model Building

Perceptron, ANN and CNN architectures

4\. Model Training

Train models using neural network layers

5\. Model Evaluation

Evaluate accuracy, loss and predictions

6\. Performance Comparison

Compare all three models and select the best

## 🧠 Deep Learning Models Implemented

### 1. Perceptron Model

A basic neural network model used as a baseline for handwritten digit classification.

- Input layer: 784 features
- Output layer: 10 neurons
- Activation function: Softmax

### 2. Artificial Neural Network (ANN)

A fully connected neural network that learns complex patterns from input images.

Architecture:

- Input layer: Flatten
- Hidden layer 1: 128 neurons (ReLU)
- Hidden layer 2: 64 neurons (ReLU)
- Output layer: 10 neurons (Softmax)

### 3. Convolutional Neural Network (CNN)

CNN is designed to extract spatial features from images using convolution and pooling operations.

Architecture:

- Convolutional layer: 32 filters
- Max Pooling layer
- Convolutional layer: 64 filters
- Max Pooling layer
- Flatten layer
- Dense layer: 128 neurons (ReLU)
- Dropout layer: 0.5
- Output layer: 10 neurons (Softmax)

## 📊 Model Performance Comparison

Best model: CNN

| Model      | Test Accuracy |
| ---------- | ------------- |
| Perceptron | 90.85%        |
| ANN        | 97.42%        |
| CNN        | 99.19%        |

Test accuracy reported by the project notebook.

0%25%50%75%100%PerceptronANNCNN

Observation: CNN achieved the highest test accuracy of 99.19%, outperforming the Perceptron and ANN models in this experiment.

## 📈 Evaluation & Visualization

The project includes:

- Training accuracy visualization
- Validation accuracy visualization
- Training and validation loss graphs
- Model accuracy comparison
- Actual vs predicted digit visualization
- CNN confusion matrix

## 🚀 How to Run the Project

Step 1: Clone the GitHub repository.

```
git clone YOUR_GITHUB_REPOSITORY_URL
```

Step 2: Install required libraries.

```
pip install numpy pandas matplotlib seaborn tensorflow scikit-learn
```

Step 3: Open the notebook using Jupyter or Google Colab.

Step 4: Upload the MNIST CSV datasets.

Step 5: Update the dataset paths in the notebook.

Step 6: Execute all notebook cells sequentially.

## 🔮 Future Enhancements

- Implement advanced CNN architectures.
- Improve model performance through hyperparameter tuning.
- Add image augmentation techniques.
- Deploy the trained model using Streamlit or Flask.
- Develop an interactive handwritten digit prediction application.
- Implement real-time digit recognition.

## 🎓 Key Learnings

- Understanding neural network architectures.
- Practical implementation of ANN and CNN.
- Image preprocessing and feature extraction.
- Model training and hyperparameter configuration.
- Deep Learning model evaluation and comparison.
- Computer Vision fundamentals.

## 👨‍💻 Author

Dnyaneshwar Sonavane

🎯 Aspiring Data Analyst | Data Science Enthusiast | Machine Learning & Deep Learning

⭐ If you find this project useful, don't forget to give the repository a star!
