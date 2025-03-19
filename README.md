# USPS-Digit-Classifier-Machine-Learning-for-Handwritten-Recognition

## USPS Dataset Classification

## Overview

This repository contains our implementation for Homework 1, where we classify USPS dataset images using K-Nearest Neighbors (kNN) and Naive Bayes classifiers. The goal was to achieve over 90% accuracy on the test set.

## Dataset

USPS Dataset: The dataset used is from Kaggle. It contains grayscale images of handwritten digits (0-9).

Format: The dataset is provided as an HDF5 file (usps.h5).

## Implementation Details

Models Used:

1) K-Nearest Neighbors (kNN) - Implemented with different values of K to analyze performance variation.

2) Naive Bayes Classifier - Applied Gaussian Naive Bayes for classification.

## Performance Evaluation

1) 10-Fold Cross-Validation: Evaluated model generalization.

2) Confusion Matrix: Visualized prediction accuracy per digit.

3) Precision & Recall: Computed per class.

4) Feature Extraction (Extra Credit): Explored SIFT-based features to enhance classification.

## Files in Repository

assignment_1/assignment-1-group-15.ipynb – Jupyter Notebook with the implementation.

assignment_1/usps.h5 – The dataset file.

REPORT-ASSIGNMENT-1.pdf – Detailed project report.

running.pdf – Execution results from the Jupyter Notebook.

## Running the Code

## Prerequisites

Ensure you have the following Python libraries installed:

## Execution

Run the Jupyter Notebook to train and evaluate the models:

## Results

Best kNN Accuracy: Achieved >90% accuracy with optimal K value.

Best Naive Bayes Accuracy: Performance was analyzed with different feature extraction methods.

Cross-Validation Results: Included in the report.
