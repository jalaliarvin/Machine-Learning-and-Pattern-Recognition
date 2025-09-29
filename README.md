### machine-learning-and-pattern-recognition
 Hands-on experience in training and evaluating ML models for rice species classification tasks

This project, undertaken as part of the Machine Learning and Pattern Recognition course, was inspired by Çınar and Koklu's research and aimed to train and assess models for image classification. The primary objective was to classify rice species using images of individual grains, drawing from a dataset containing 100 images per rice species selected from a larger pool of 75,000 images.

Feature extraction involved analyzing color features derived from YCbCr-color channel values and morphological features obtained from rice grain contours. Exploratory data analysis techniques such as histograms, pair plots, and Principal Component Analysis (PCA) were utilized to gain insights into the dataset.

For classification, three classifiers such as Random Forest (RF), Support Vector Machine (SVM), and Multi-Layer Perceptron (MLP) were employed. Model selection was conducted through hyperparameter tuning and 5-fold cross-validation with three repetitions. Nested cross-validation was utilized to estimate model performance, resulting in mean accuracies of 0.994 for RF, 0.998 for SVM, and 0.968 for MLP.

It's noteworthy that morphological and shape features played significant roles in classification accuracy. This project provided valuable practical experience in training and evaluating machine learning models for image classification tasks, offering insights into feature importance and model performance.
