# Phishing Website Detection using Machine Learning

## Project Description

This project was developed as part of the **Data Science in Cybersecurity** course at the **University of Haifa**.

The objective of this project is to reproduce and critically evaluate a published phishing website detection study using machine learning techniques. The project follows a complete machine learning pipeline, including data exploration, preprocessing, feature engineering, model training, evaluation, and error analysis.

Two supervised machine learning models were implemented and compared:

- Logistic Regression
- Random Forest

The implementation was developed using **Python** in **Google Colab**.
## Critical Evaluation

This project reproduces and critically evaluates the methodology presented in the original paper.

Several improvements were introduced compared to the original implementation:

- Duplicate records were identified and analyzed.
- Feature selection was performed only on the training set to eliminate data leakage.
- Additional cybersecurity evaluation metrics (MCC, PR-AUC, F2-score) were computed.
- Threshold tuning was performed to study the Precision–Recall trade-off.
- Error analysis examined False Positives and False Negatives from a cybersecurity perspective.
The dataset was also inspected for duplicate records, and experiments confirmed that removing duplicate samples did not materially affect model performance.
Feature selection was performed exclusively on the training set to prevent information leakage into the test data.

---

## Selected Research Paper

**Phishing Websites Dataset for Machine Learning**

Data in Brief, Volume 33, 2020

https://www.sciencedirect.com/science/article/pii/S2352340920313202

---

## Original GitHub Repository

The original implementation that inspired this project is available at:

https://github.com/GregaVrbancic/Phishing-Dataset

---

## Dataset Source

The dataset used in this project is the phishing website dataset introduced in the research paper above.

Dataset characteristics:

- **58,645 website samples**
- **112 extracted features**
- Binary classification task:
  - **0** = Legitimate Website
  - **1** = Phishing Website

This repository includes the dataset used in the notebook:

```
data/dataset_small.csv
```

---

## Repository Structure

```
phishing-website-detection/
│
├── data/
│   └── dataset_small.csv
│
├── cyber_phishing_detection.ipynb
├── report.pdf
├── README.md
├── requirements.txt
```

---

## Project Workflow

The notebook includes the following stages:

- Data loading and inspection
- Missing value analysis
- Duplicate analysis
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Leakage-Free Feature Selection
- Feature Scaling
- Logistic Regression
- Random Forest
- Model Evaluation
- Threshold Tuning
- Feature Importance Analysis
- ROC Curve Analysis
- Error Analysis
---

## Results Summary

Both machine learning models achieved strong performance in detecting phishing websites.

Random Forest consistently outperformed Logistic Regression across Accuracy, Precision, Recall, F1-score, F2-score, ROC-AUC, PR-AUC, and MCC.

Threshold tuning further demonstrated the trade-off between Precision and Recall, highlighting the importance of selecting an operating threshold for cybersecurity applications.
---

## Requirements

Python **3.10** or newer.

All required packages are listed in requirements.txt.

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

## Execution Instructions

1. Clone this repository.

```bash
git clone https://github.com/Mrahelm/phishing-website-detection.git
```

2. Open **cyber_phishing_detection.ipynb** using **Google Colab** or **Jupyter Notebook**.

3. Verify that the dataset is located at:

```
data/dataset_small.csv
```

4. If necessary, update the dataset path inside the notebook.

5. Run all notebook cells from top to bottom.

---
## References

### Research Paper

M. S. A. Aljabri, S. Aljameel, I. Alsmadi, et al.

**Phishing Websites Dataset for Machine Learning**

Data in Brief, Volume 33, 2020.

https://www.sciencedirect.com/science/article/pii/S2352340920313202

### Original GitHub Repository

https://github.com/GregaVrbancic/Phishing-Dataset

---

## Author

**Tasneem Mrahel**

B.Sc. Computer Science

University of Haifa
