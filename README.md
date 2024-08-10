# Heart Disease Classification using Machine Learning Algorithms

This repository contains the code and documentation for a project focused on classifying heart disease using machine learning algorithms. The goal of the project is to predict the presence of heart disease in patients based on a set of predictive attributes.

## Project Overview

Heart disease is one of the leading causes of death globally. Early detection and accurate classification are crucial for effective treatment and management. In this project, we utilize machine learning algorithms to classify heart disease based on various patient attributes. The project demonstrates the use of Random Forest and Support Vector Machine algorithms, among others, to achieve a classification accuracy of over 90%.

## Data

The dataset used in this project is sourced from the UCI Machine Learning Repository and contains 3,000+ patient records. Each record includes 13 predictive attributes such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

## Algorithms Used

The following machine learning algorithms were implemented in this project:

- **Random Forest**: A powerful ensemble learning method that operates by constructing a multitude of decision trees and outputting the mode of the classes.
- **Support Vector Machine (SVM)**: A supervised learning model that analyzes data for classification by finding the optimal hyperplane that maximizes the margin between different classes.
- **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that classifies data points based on the majority class of their nearest neighbors.
- **Logistic Regression**: A statistical model that in this case uses a logistic function to model a binary dependent variable.
- **AdaBoost**: An ensemble learning algorithm that combines the predictions of multiple weak classifiers to improve accuracy.
- **Naive Bayes**: A classification technique based on Bayes' theorem with an assumption of independence between predictors.
- **Decision Tree**: A non-parametric supervised learning method used for classification that models decisions and their possible consequences as a tree structure.

Additionally, feature selection techniques and hyperparameter tuning were applied to improve the models' performance.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Jagadeesh-N/Heart-Disease-Classification-Using-Machine-Learning-Algorithms.git
    ```
2. Navigate to the project directory:
    ```bash
    cd heart-disease-classification
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

After installation, you can run the notebook to train and evaluate the models:

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Heart_Disease_Classification.ipynb
    ```
2. Run the cells to execute the code. The notebook will guide you through the steps of data preprocessing, model training, and evaluation.

## Results

## Results

- The implemented algorithms, including Random Forest, SVM, KNN, AdaBoost, Logistic Regression, Naive Bayes, Decision Tree, and Gradient Boosting, were used to classify heart disease with varying degrees of success.
- The Random Forest and SVM models achieved the highest classification accuracy, both exceeding 90%.
- Feature selection and hyperparameter tuning across all models contributed to reducing false positive rates by 15% and optimizing overall performance.
- The final ensemble model combining multiple algorithms provided robust predictions, making it a valuable tool for early detection of heart disease.
