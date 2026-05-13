# Comment Category Prediction Challenge

## Overview

This project focuses on building a machine learning pipeline for predicting comment categories using textual content and metadata features. The notebook performs complete exploratory data analysis (EDA), preprocessing, feature engineering, model building, and prediction generation using classical machine learning and boosting algorithms.

The project was developed in a Kaggle environment and demonstrates an end-to-end Natural Language Processing (NLP) workflow using Python.

---

# Project Objectives

* Analyze comment-based datasets
* Perform text preprocessing and feature engineering
* Handle missing values and categorical features
* Generate TF-IDF text features
* Train and evaluate machine learning models
* Predict comment categories
* Build a complete NLP classification pipeline

---

# Features

* Exploratory Data Analysis (EDA)
* Text Cleaning and Preprocessing
* Missing Value Handling
* DateTime Feature Engineering
* TF-IDF Vectorization
* Sparse Matrix Feature Combination
* Logistic Regression Model
* XGBoost Classifier
* LightGBM Integration
* Stratified Train-Test Splitting
* Accuracy Evaluation
* Visualization using Seaborn and Matplotlib

---

# Tech Stack

| Category             | Technologies        |
| -------------------- | ------------------- |
| Programming Language | Python              |
| Data Analysis        | Pandas, NumPy       |
| Visualization        | Matplotlib, Seaborn |
| Machine Learning     | Scikit-learn        |
| Gradient Boosting    | XGBoost, LightGBM   |
| NLP                  | TF-IDF Vectorizer   |
| Environment          | Kaggle Notebook     |

---

# Dataset Information

The dataset contains:

* User comments
* Upvotes and downvotes
* Emoticon-based features
* Timestamps
* Comment labels/categories

The objective is to predict the final category label for each comment.

---

# Project Workflow

## 1. Data Loading

Datasets are loaded using Pandas:

* `train.csv`
* `test.csv`
* `Sample.csv`

---

## 2. Exploratory Data Analysis

Performed:

* Dataset shape inspection
* Feature distribution analysis
* Class imbalance analysis
* Correlation heatmaps
* Comment length analysis
* Upvote/downvote distribution analysis

Visualizations were created using:

* Seaborn
* Matplotlib

---

## 3. Data Preprocessing

The notebook includes:

* Missing value handling
* Text cleaning using regular expressions
* Date conversion and extraction
* Removal of unnecessary columns
* Identity feature handling
* Encoding categorical features

---

## 4. Feature Engineering

### Text Features

TF-IDF vectorization was applied on comment text.

### Numerical Features

Features such as:

* Upvotes
* Downvotes
* Emoticon counts

were included.

### Datetime Features

Extracted time-based information from timestamps.

### Sparse Feature Combination

Combined text and structured features using sparse matrices.

---

## 5. Model Building

The following models were used:

### Logistic Regression

Baseline linear classification model.

### XGBoost Classifier

Gradient boosting model for improved performance.

### LightGBM

Efficient boosting framework for large-scale learning.

---

## 6. Model Evaluation

The notebook evaluates model performance using:

* Accuracy Score
* Validation Splits
* Stratified Cross Validation

---

# Project Structure

```txt
project/
│
├── notebooks/
│   └── comment-category-prediction.ipynb
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── Sample.csv
│
├── requirements.txt
├── README.md
└── outputs/
```

---

# Installation

## Clone the Repository

```bash
git clone <your-github-repo-link>
cd <repository-name>
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Notebook

Open Jupyter Notebook or Kaggle Notebook and run:

```bash
jupyter notebook
```

Then open:

```txt
comment-category-prediction.ipynb
```

---

# Sample Requirements.txt

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
lightgbm
scipy
jupyter
```

---

# Key Learnings

This project demonstrates:

* NLP preprocessing workflows
* Text classification techniques
* Feature engineering strategies
* Machine learning model training
* Handling imbalanced datasets
* End-to-end ML pipeline development

---

# Future Improvements

* Deep Learning Models (LSTM/BERT)
* Hyperparameter Optimization
* Better Imbalance Handling
* Model Deployment with Flask/FastAPI
* Interactive Dashboard Integration

---

# Author

Pratyush Pulak Nishank

---

# License

This project is intended for educational and portfolio purposes.
