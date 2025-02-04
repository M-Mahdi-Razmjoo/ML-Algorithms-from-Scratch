# ML-Algorithms-from-Scratch

This repository contains custom implementations of key machine learning algorithms built entirely from scratch in Python. The project is divided into two main parts:

## Overview

- **Logistic Regression:**  
  Implements binary classification using the sigmoid function, binary cross-entropy loss, and gradient descent optimization. Tested on both dummy datasets and real-world examples such as the Breast Cancer dataset and Rotten Tomatoes Reviews for sentiment analysis. Features include loss tracking, validation accuracy monitoring, and visualization of decision boundaries.

- **Decision Tree:**  
  Contains two versions of a Decision Tree implementation:
  1. A basic version that treats all features uniformly.
  2. An improved version that handles numerical features with threshold-based splits (using entropy and information gain) to yield better splits and generalization.
  
  The Decision Trees are evaluated on the Bank Marketing dataset from the UCI Repository, which includes a mix of numerical and categorical data.

## Project Structure

- `logistic_regression.py` – Contains the implementation of Logistic Regression with gradient descent.
- `decision_tree.py` – Includes both the basic and improved implementations of Decision Trees.
- `notebooks/` – Jupyter notebooks demonstrating the application of these models on various datasets.
- `data/` – Sample datasets used in the experiments (e.g., Breast Cancer, Rotten Tomatoes Reviews, Bank Marketing).
