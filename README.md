# Comprehensive Analysis and Prediction of Titanic Passengers' Survival Using Machine Learning

<img src="https://github.com/basapacheco/Titanic/blob/main/Titanic.jpg">

This project focuses on predicting the survival of Titanic passengers by using machine learning algorithms and conducting a comprehensive data analysis.

## Libraries Used

- Python 3
- Numpy
- Pandas
- Matplotlib
- Scikit-learn

## Project Steps

1. **Importing Libraries and Loading Data**
    - Imported all necessary libraries and loaded the training and test datasets.

2. **Descriptive Statistics and Initial Analysis**
    - Grouped data by survival status and calculated mean values for numeric columns.
    - Conducted an initial analysis to identify differences in average age, fare, and class between survivors and non-survivors.

3. **Gender Analysis and Visualisation**
    - Counted the number of male and female passengers onboard.
    - Visualised gender distribution and analysed survival rates by gender.

4. **Class and Age Analysis**
    - Visualised survival by ticket class.
    - Analysed age distribution of survivors and non-survivors.

5. **SibSp, Pclass, Age, and Embarked Analysis**
    - Analysed survival rates based on the number of siblings/spouses onboard, class, age, and embarkation point.
    - Visualised survival rates by embarkation point.

6. **Data Preprocessing**
    - Dropped unnecessary columns.
    - Selected relevant features and handled missing values.
    - Converted categorical variables to numeric.

7. **Model Training and Evaluation**
    - Trained and evaluated various machine learning models:
        - Logistic Regression
        - Support Vector Machine (SVM)
        - K-Nearest Neighbours (KNN)
        - Naive Bayes
        - Decision Tree
    - Compared model accuracies and selected the best model.

8. **Generating Predictions and Explaining Results**
    - Used the best model to make predictions on the test set.
    - Generated a CSV file with the predictions.
    - Created a detailed report in TXT format explaining the results and conclusions of the analysis.

## Results

- **Best Model:** Naive Bayes
- **Model Accuracy:** 0.77

## Detailed Report

At the end of the analysis, a detailed report in TXT format summarises the steps followed, analyses performed, and conclusions drawn.

---

## Running the Project

To run this project, follow these steps:

1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Execute the Jupyter Notebook script to perform the analysis and generate predictions.

---

This project provides a comprehensive understanding of the factors that influenced the survival of Titanic passengers, using data analysis and machine learning techniques.