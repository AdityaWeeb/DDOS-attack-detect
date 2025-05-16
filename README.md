# 🚨 Blockchain DDoS Attack Detection using Deep Learning (CNN & RNN)

This project implements a deep learning-based approach to detect Distributed Denial-of-Service (DDoS) attacks in blockchain environments. It leverages both Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) to process network traffic data and identify malicious behavior with high accuracy.

## 📁 Dataset
> The dataset used must be loaded before running the model. Please make sure to place it correctly in the working directory or mount it via Google Drive if using Colab.

## 🛠️ Preprocessing
- Combined multiple feature sets to form a unified dataset.
- Applied normalization and reshaping for CNN input compatibility.
- Split data into training and testing sets.

## 🧠 Models Used
### Convolutional Neural Network (CNN)
- Designed to capture spatial patterns in input features.
- Effective in feature extraction from fixed-length input sequences.

### Recurrent Neural Network (RNN)
- Captures temporal dependencies in traffic data.
- Useful for analyzing time-series nature of attack behaviors.

## 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix and Loss/Accuracy curves

## 🔍 Results
> *(Replace this with actual accuracy and loss values from your final output)*  
Example:  
- CNN Accuracy: 95.6%  
- RNN Accuracy: 93.4%  
- F1-score (CNN): 0.94

