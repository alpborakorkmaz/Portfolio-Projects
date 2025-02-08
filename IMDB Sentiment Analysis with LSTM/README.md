## IMDB Sentiment Analysis with LSTM

## Description

This project implements a Long Short-Term Memory (LSTM) neural network for sentiment analysis on the IMDB movie reviews dataset. The dataset consists of movie reviews labeled as positive or negative. The model is designed to classify reviews based on their sentiment after preprocessing and training.

## Implementation Details

- **Dataset:** IMDB Movie Reviews
- **Preprocessing:** Tokenization, padding, and embedding of sequences
- **Model Architecture:** Embedding layer followed by an LSTM layer
- **Optimization:** Early stopping and model checkpointing
- **Libraries Used:** TensorFlow, Keras, NumPy, Matplotlib

## Results

The trained model was evaluated on the test set, demonstrating strong sentiment classification performance. Metrics such as accuracy and loss were tracked, and the results confirmed that LSTMs are effective for natural language processing tasks like sentiment analysis.
