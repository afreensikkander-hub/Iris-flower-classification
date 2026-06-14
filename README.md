# Iris-flower-classification
# Iris Flower Classification Using Machine Learning

## Project Overview

This project aims to classify iris flowers into different species using machine learning algorithms. The dataset contains measurements of sepal length, sepal width, petal length, and petal width. Multiple machine learning models were trained and compared to determine the best-performing classifier.

## Dataset

* Dataset: Iris Dataset
* Source: Kaggle / UCI Machine Learning Repository
* Total Records: 150
* Features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* Target Variable:

  * Species

## Project Steps

### 1. Data Loading and Exploration

* Loaded the dataset using Pandas.
* Checked dataset shape, data types, and missing values.
* Generated summary statistics.

### 2. Exploratory Data Analysis (EDA)

* Species distribution count plot.
* Histograms of numerical features.
* Correlation heatmap.
* Pairplot for feature relationships.

### 3. Data Preprocessing

* Removed unnecessary columns if present.
* Encoded the target variable using LabelEncoder.
* Split data into training and testing sets (80:20).

### 4. Feature Engineering

* Analyzed feature correlations.
* Identified important features contributing to classification.

### 5. Model Training

Three machine learning models were trained:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier

### 6. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

### 7. Best Model Selection

The best-performing model was selected based on evaluation metrics and analyzed using a confusion matrix.

## Results

The trained models achieved high classification performance on the Iris dataset. Random Forest provided the best overall performance and demonstrated strong predictive capability.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## Project Structure

Project02/

├── Iris.xlsx (or Iris.csv)

├── Iris_Classification.ipynb

├── README.md

## Conclusion

This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and comparison. Among the tested models, Random Forest achieved the best performance for Iris species classification.

