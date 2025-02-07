# Recipe Site Traffic - DataCamp Final Project

## Table of contents
* [General info](#general-info)
* [Libraries](#libraries)
* [Results](#results)

## General info
Repository contains my final project (practical exam) for Data Scientist certification on DataCamp platform. The goal was to predict which recipes will generate high traffic on a fictional website using historic data with 80% success rate. 

## Libraries
The project has a form of Jupyter Notebook. I used following Python libraries: Pandas, Numpy, Scikit-learn, seaborn, matplotlib.pyplot, missingno.

## Results
After data cleaning, dealing with outliers and visual analysis, two machine learning models were chosen for binary classification. Logistic Regression model was trained as a baseline model, and second approach was Random Forest Classifier. 3 metrics were chosen to evaluate models performance to fully captute nuances of the data: recall, precision and f-1 score. After comparison it turned out that Logistic Regression model performs slightly better, meeting set criteria in all chosen metrics.
