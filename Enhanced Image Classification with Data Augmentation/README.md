## Enhanced Image Classification with Data Augmentation

## Description

This project applies data augmentation techniques to improve image classification using the CIFAR-10 dataset. The dataset consists of 10 different object categories, and the goal is to enhance model generalization by introducing transformations to the training images. A convolutional neural network (CNN) is implemented to classify the images effectively.

## Implementation Details

- **Dataset:** CIFAR-10 Image Dataset
- **Preprocessing:** Image normalization and one-hot encoding of labels
- **Data Augmentation:** Rotation, flipping, zooming, and shifting using Keras ImageDataGenerator
- **Model Architecture:** CNN with convolutional, pooling, and dense layers
- **Optimization:** RMSprop optimizer with dropout layers to prevent overfitting
- **Libraries Used:** TensorFlow, Keras, Matplotlib, scikit-learn

## Results

The model was trained with and without data augmentation, and the results showed a significant improvement in classification accuracy with augmented data. Evaluation metrics such as accuracy and loss were analyzed, and classification reports were generated to assess the model’s performance.
