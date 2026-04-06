# Logistic Regression Assignment


## Objective of the Assignment

The objective of this assignment is to apply Logistic Regression to predict whether a user will click on an advertisement based on different user features such as age, income, internet usage, and time spent on a website. The assignment also demonstrates how to perform data exploration, visualization, model training, prediction, and evaluation using Python and machine learning libraries.

---

## Dataset Description

The dataset used in this assignment is **advertising.csv**. It contains information about users and their interaction behavior with advertisements.

Main attributes in the dataset:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Male
* Clicked on Ad (Target Variable)

The target variable **Clicked on Ad** indicates whether the user clicked on the advertisement (1) or not (0).

---

## Libraries Used

The following Python libraries were used to complete this assignment:

* Pandas (for data handling)
* NumPy (for numerical operations)
* Matplotlib (for visualization)
* Seaborn (for advanced visualization)
* Scikit-learn (for machine learning model implementation)

---

## Steps Performed in the Assignment

### 1. Importing Libraries

Required libraries such as pandas, numpy, seaborn, matplotlib, and sklearn were imported to perform analysis and modeling.

### 2. Loading the Dataset

The dataset was loaded using pandas and examined using:

* head()
* info()
* describe()

These functions helped understand the structure and statistical summary of the dataset.

### 3. Exploratory Data Analysis (EDA)

Data visualization techniques were used to explore relationships between variables:

* Histogram of Age distribution
* Jointplot between Age and Area Income
* KDE jointplot between Age and Daily Time Spent on Site
* Jointplot between Daily Time Spent on Site and Daily Internet Usage
* Pairplot grouped by Clicked on Ad

These visualizations helped identify patterns in user behavior.

### 4. Feature Selection

Only relevant numerical features were selected for model training:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Male

Text-based features were excluded because logistic regression works with numerical values.

### 5. Splitting the Dataset

The dataset was divided into:

* Training set (70%)
* Testing set (30%)

This helps evaluate model performance on unseen data.

### 6. Training the Logistic Regression Model

A Logistic Regression model was created using Scikit-learn and trained using the training dataset.

### 7. Making Predictions

Predictions were generated using the testing dataset.

### 8. Model Evaluation

The performance of the model was evaluated using a classification report that includes:

* Precision
* Recall
* F1-score
* Accuracy

These metrics measure how well the model predicts whether a user clicks on an advertisement.

---

## Results

The logistic regression model successfully predicted whether a user would click on an advertisement using behavioral and demographic features. The classification report showed strong prediction accuracy, indicating that the selected features were effective for classification.

---

## Conclusion

This assignment demonstrated how logistic regression can be applied to a real-world dataset to solve a classification problem. It also provided hands-on experience with data preprocessing, visualization, model training, and evaluation using Python machine learning libraries.

Logistic Regression is a powerful and efficient algorithm for binary classification problems such as advertisement click prediction.

---

## Tools and Environment

Programming Language: Python
Platform: Jupyter Notebook (Anaconda Navigator)
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Dataset: advertising.csv

---

Prepared by: _______________________


