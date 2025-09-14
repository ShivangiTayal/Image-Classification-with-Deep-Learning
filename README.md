# Image-Classification-with-Deep-Learning
Created a CNN using TensorFlow/Keras for handwritten digit recognition on the MNIST dataset. Applied EarlyStopping and ModelCheckpoint to prevent overfitting, achieving ~91% accuracy and visualizing predictions with Plotly for better interpretability.
📌 Project Overview

This project builds a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

📂 Dataset

Dataset: MNIST Handwritten Digit Dataset (70,000 grayscale images).

Each image: 28x28 pixels, labeled from 0–9.

🔑 Approach

Data Preparation

Normalized pixel values (0–255 → 0–1).

One-hot encoded labels.

Modeling

Built a CNN with Conv2D, MaxPooling, Dense, Dropout layers.

Used EarlyStopping and ModelCheckpoint to prevent overfitting.

Evaluation

Evaluated with accuracy and loss curves.

Visualized predictions with Plotly.

📊 Results

Achieved ~91% accuracy on MNIST test set.

Model generalized well with minimal overfitting.

🛠️ Tech Stack

Python, TensorFlow/Keras, CNN, Deep Learning, Plotly
