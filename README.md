# Amazon Review Star-Rating Classifier (1–5 Stars)

This project builds a deep learning text classifier that predicts Amazon product review star ratings (1–5) using review text.

## What it does
- Loads Amazon review data (`Reviews.csv`)
- Creates a balanced dataset (equal samples per star rating)
- Tokenizes and pads text sequences
- Trains a neural network (Embedding → Pooling → Dense → Softmax)
- Evaluates test accuracy and prints misclassified examples

## Tech Stack
- Python
- TensorFlow / Keras
- pandas, numpy
- scikit-learn

## Project Structure (suggested)
