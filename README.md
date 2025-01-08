# churn_modeling

# Customer Churn Prediction

This project uses a deep learning approach to predict customer churn based on various features from a dataset. The model is built using TensorFlow and trained on preprocessed data with techniques such as one-hot encoding, feature scaling, and dropout for regularization.

## Features

- Data Preprocessing:
  - One-hot encoding for categorical variables like `Geography` and `Gender`.
  - Feature scaling using `StandardScaler` to normalize data.
  - Train-test split for effective model evaluation.

- Model Architecture:
  - A neural network with multiple layers using the TensorFlow library.
  - ReLU activation for hidden layers and sigmoid activation for binary classification.
  - Dropout layers to reduce overfitting.

- Optimization and Training:
  - Adam optimizer with a custom learning rate.
  - Binary cross-entropy loss function.
  - Early stopping to prevent overfitting and optimize training.

- Performance Metrics:
  - Confusion matrix for evaluating prediction outcomes.
  - Accuracy score for model performance.

## Tools and Libraries

- Libraries: 
  - `tensorflow` 
  - `numpy` 
  - `matplotlib` 
  - `pandas` 
  - `sklearn`

- Dataset: 
  - Customer churn data (CSV format)

## Visual Highlights

- Model Accuracy and Loss:
  - Plots showing training and validation accuracy over epochs.
  - Loss curves to analyze the model's performance during training.

- Confusion Matrix:
  - A detailed visualization of true positive, true negative, false positive, and false negative predictions.

## Insights and Results

- The model effectively predicts customer churn with a high accuracy score.
- Regularization techniques like dropout and early stopping improve generalization.
- Feature engineering (e.g., one-hot encoding) enhances model performance.

