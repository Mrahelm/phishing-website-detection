# Phishing Website Detection using Machine Learning

## Project Overview

This project investigates the use of machine learning techniques to detect phishing websites based on URL-based and domain-related features.

The project follows a complete machine learning pipeline, including data exploration, preprocessing, feature engineering, model training, evaluation, and error analysis.

The implementation was developed in Google Colab using Python.

---

## Dataset

The dataset contains **58,645 website samples** with **112 features** describing URL structure, domain characteristics, DNS information, SSL certificates, response time, and other cybersecurity-related attributes.

Target variable:

- **0** = Legitimate Website
- **1** = Phishing Website

---

## Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset inspection
- Feature types
- Missing value analysis
- Duplicate analysis
- Single-value feature analysis
- Feature distributions
- Outlier analysis
- Temporal feature analysis
- Class imbalance analysis
- Group-by analysis
- Correlation analysis using **Spearman correlation**

---

## Feature Engineering

The preprocessing pipeline includes:

- Removal of irrelevant (single-value) features
- Feature scaling using StandardScaler (for Logistic Regression)
- Feature selection
- Train/Test split using stratified sampling

---

## Machine Learning Models

Two supervised machine learning models were trained and evaluated:

- Logistic Regression
- Random Forest

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- Classification Report

---

## Results

The Random Forest model achieved the best overall performance.

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|-------|---------:|----------:|--------:|---------:|---------:|
| Logistic Regression | 0.8245 | 0.8402 | 0.8200 | 0.8300 | 0.8972 |
| Random Forest | 0.8436 | 0.8455 | 0.8572 | 0.8513 | 0.9161 |

---

## Repository Structure

```
phishing-website-detection/
│
├── phishing_detection.ipynb
├── README.md
└── report.pdf
```

---

## Requirements

Python 3.10+

Required libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Running the Project

1. Clone the repository.

```bash
git clone https://github.com/Mrahelm/phishing-website-detection.git
```

2. Open the notebook in **Google Colab** or **Jupyter Notebook**.

3. Download the dataset.

4. Update the dataset path if necessary.

5. Run all notebook cells.

---

## References

### Dataset

The phishing website dataset used in this project is based on the publicly available dataset from:

https://www.unb.ca/cic/datasets/url-2016.html

### Related Research

S. Marchal, J. Francois, R. State, and T. Engel,
"PhishStorm: Detecting Phishing With Streaming Analytics."

---

## Author

Tasneem Mrahel

University of Haifa

Computer Science
