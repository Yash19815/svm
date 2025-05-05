# Iris Species Detection Using Support Vector Machine (SVM)

This project demonstrates the use of Support Vector Machine (SVM) to classify different species of the Iris flower based on the classic **Iris dataset**. It is a simple machine learning project ideal for beginners and serves as an introduction to classification using SVM.

## What is SVM?

**Support Vector Machine (SVM)** is a supervised machine learning algorithm commonly used for classification and regression tasks. The key idea behind SVM is to find the optimal hyperplane that best separates data points of different classes in a feature space.

- In binary classification, SVM tries to find a hyperplane that maximizes the margin between two classes.
- For multi-class problems like the Iris dataset, SVM uses strategies such as "one-vs-rest" or "one-vs-one".

SVM is effective in high-dimensional spaces and is memory efficient since it uses a subset of training points (support vectors) to make decisions.

##  The Iris Dataset

The Iris dataset is a well-known dataset in machine learning and statistics. It includes 150 samples from three species of Iris (Iris setosa, Iris versicolor, and Iris virginica), with four features for each sample:

- Sepal length
- Sepal width
- Petal length
- Petal width

## Project Workflow

1. **Data Loading**: Load the Iris dataset using `sklearn.datasets`.
2. **Data Preprocessing**: Split the dataset into training and test sets.
3. **Model Training**: Train an SVM classifier using `sklearn.svm.SVC`.
4. **Prediction & Evaluation**: Use the trained model to predict test data and evaluate accuracy.

## Technologies Used

- Python 3
- scikit-learn
- NumPy
- Matplotlib (optional, for visualization)
