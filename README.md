### Training and Evaluating ML Models for Rice Species Classification Tasks

This project, part of the Machine Learning and Pattern Recognition course at the University of Turku, aimed to train and evaluate models for image classification. Inspired by Çınar and Koklu's work, the task focused on classifying rice species using images of individual rice grains. The dataset comprised 100 images per rice species, extracted from a larger dataset of 75,000 images.

Features were extracted from the rice images, including color features derived from YCbCr-color channel values and morphological features obtained from contours of rice grains. Data analysis techniques such as histograms, pair plots, and Principal Component Analysis (PCA) were used for exploration.

Three classifiers including Random Forest (RF), Support Vector Machine (SVM), and Multi-Layer Perceptron (MLP) were employed for classification. Model selection involved hyperparameter optimization and 5-fold cross-validation with three repetitions. Nested cross-validation was used to estimate model performance, resulting in mean accuracies of 0.994 for RF, 0.998 for SVM, and 0.968 for MLP.

Notably, morphological and shape features emerged as significant contributors to classification. This exercise provided valuable hands-on experience in training and evaluating ML models for image classification tasks.
