# Skin Disorder Classification

## Project Overview

This project focuses on analyzing dermatology patient data and building a machine learning classification model to identify different types of skin disorders based on clinical symptoms and patient characteristics.

The dataset contains 366 patient records with 34 symptom-related features, Age, and a target class representing six different disease categories.

## Problem Statement

To analyze clinical symptoms and patient characteristics and develop a machine learning classification approach for predicting the type of skin disorder.

## Dataset

* Number of records: 366
* Number of columns: 35
* Input features: 34 clinical/symptom features and Age
* Target variable: `class`
* Target classes: 1–6

The symptom attributes are represented using numerical scores.

## Project Workflow

1. Data Loading
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Visualization
6. Feature and Target Separation
7. Train-Test Split
8. Model Building
9. Model Evaluation
10. Comparison of Models
11. Final Conclusions

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning

The project uses supervised machine learning classification techniques to predict the skin disorder class from the available clinical features.

## Key Analysis

The notebook explores the distribution of the target classes, relationships among clinical features, data quality, and model performance.

## Repository Contents

```text
├── README.md
├── PRCP-1027-Skin Disorder (1).ipynb
├── dataset/
├── images/
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone this repository.
2. Install the required Python packages.
3. Open the Jupyter Notebook.
4. Make sure the dataset is available in the `dataset` folder.
5. Run the notebook cells sequentially.

## Conclusion

This project demonstrates an end-to-end machine learning workflow for multiclass skin disorder classification, starting from data exploration and preprocessing through model development and evaluation.
