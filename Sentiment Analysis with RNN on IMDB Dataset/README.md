## Sentiment Analysis with RNN on IMDB Dataset

## Description

This project implements a Recurrent Neural Network (RNN) to perform sentiment analysis on the IMDB movie reviews dataset. The dataset contains positive and negative movie reviews, and the goal is to classify each review based on its sentiment. The model is trained using an embedding layer and a SimpleRNN layer.

## Implementation Details

- **Dataset:** IMDB Movie Reviews
- **Preprocessing:** Tokenization and padding of sequences
- **Model Architecture:** Embedding layer followed by a SimpleRNN layer
- **Optimization:** Early stopping and hyperparameter tuning with Keras Tuner
- **Libraries Used:** TensorFlow, Keras, Matplotlib, scikit-learn

## Results

The trained model was evaluated on a test set, achieving a strong classification performance. ROC curves and AUC scores were analyzed to assess the model’s effectiveness. The results indicate that RNN-based sentiment analysis can successfully classify movie reviews with high accuracy.
