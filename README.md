
# 🧠 Spam Email Classification — Neural Network Project

### This project uses a Sequential Neural Network built with TensorFlow and Keras to classify emails as spam or non-spam.

## 📊 Project Overview

Goal: Predict whether an email is spam or not using supervised learning.

Tech Stack: Python, TensorFlow, Keras, NumPy, Pandas, scikit-learn.

Model Type: Multi-layer feedforward neural network.

Performance:

  Accuracy: 93.6%

  Precision: 92.9%

  Recall: 90.6%

  F1 Score: 91.8%

## ⚙️ Steps:

Data loading and preprocessing

Neural network creation with Keras Sequential API

Model compilation, training, and tuning (batch size & epochs)

Model evaluation using accuracy, precision, F1 score, and recall

## 🔍 Key Insights:

Increasing epochs improved learning until overfitting occurred.

Best configuration: batch size = 64, epochs = 20.

Model shows a strong balance between detecting spam and avoiding false alarms.
