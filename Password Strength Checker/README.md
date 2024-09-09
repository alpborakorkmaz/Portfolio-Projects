# Password Strength Checker

## Overview

This project is a **Password Strength Checker** that uses machine learning to predict the strength of a password as *Weak*, *Medium*, or *Strong*. The model is trained using password datasets and evaluates the strength of passwords based on their features.

## Features

- Uses **TfidfVectorizer** to extract features from passwords.
- Employs a **RandomForestClassifier** to train a model that classifies passwords into three categories: *Weak*, *Medium*, and *Strong*.
- Achieves a model accuracy of approximately **95%** on test data.
- Allows users to input passwords interactively and predicts the password strength.
