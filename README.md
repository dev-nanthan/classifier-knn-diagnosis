# Alzheimer’s Disease Diagnosis using KNN Classifier

## Overview
This project aims to develop a K-Nearest Neighbors (KNN) classifier to differentiate between stable Normal Controls (sNC) and stable Dementia of Alzheimer’s Type (sDAT) based on glucose metabolism in specific brain regions. By analyzing glucose metabolism patterns, the model predicts the likelihood of Alzheimer's Disease in individuals.

## Technical Explanation

### Data Preprocessing
The initial step involves preprocessing data from two brain regions, the isthmus cingulate and precuneus, to standardize features for the KNN classifier. This step is crucial for removing biases due to scale differences in the measurements.

### KNN Classifier
The core of the project is the implementation of the KNN algorithm, which classifies samples based on the closest training examples in the feature space. The classifier is tested with different values of `k` to optimize its performance, utilizing Euclidean and Manhattan distances to measure similarity.

### Performance Evaluation
Classifier performance is evaluated through error rates on both training and independent test datasets. Visualization of classification boundaries and error rates for various `k` values and distance metrics provide insights into the model's accuracy and robustness.

### Model Optimization
The project explores different strategies to enhance the KNN classifier's performance, including adjusting the number of neighbors (`k`) and experimenting with distance metrics. The objective is to minimize error rates and improve predictive accuracy for Alzheimer’s Disease diagnosis.

## Conclusion
Through careful model tuning and evaluation, this project demonstrates the potential of KNN classifiers in medical diagnostics, specifically in early detection of Alzheimer’s Disease based on glucose metabolism signatures in the brain.
