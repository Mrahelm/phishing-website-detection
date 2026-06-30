# Phishing Website Detection using Machine Learning

## Project Description

This project was developed as part of the **Data Science in Cybersecurity** course at the **University of Haifa**.

The objective of the project is to reproduce and critically evaluate a published phishing website detection study. The project follows a complete machine learning workflow, including data exploration, preprocessing, feature engineering, model training, evaluation, and error analysis.

Two machine learning models were implemented and compared:

- Logistic Regression
- Random Forest

The experiments were performed in Python using Google Colab.

---

# Selected Research Paper

**Phishing Websites Dataset for Machine Learning**

Data in Brief, Volume 33, 2020

https://www.sciencedirect.com/science/article/pii/S2352340920313202

---

# Original GitHub Repository

The implementation provided by the original authors can be found here:

https://github.com/GregaVrbancic/Phishing-Dataset

---

# Dataset Source

The dataset used in this project is the phishing website dataset introduced in the above publication.

Dataset information:

- 58,645 website samples
- 112 extracted features
- Binary classification
    - 0 = Legitimate Website
    - 1 = Phishing Website

The dataset is available through the original GitHub repository and the accompanying publication.

---

# Repository Structure

```
phishing-website-detection/
│
├── phishing_detection.ipynb
├── report.pdf
└── README.md
```

---

# Requirements

Python 3.10 or newer

Required libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

# Execution Instructions

1. Clone this repository.

```bash
git clone https://github.com/Mrahelm/phishing-website-detection.git
```

2. Open `phishing_detection.ipynb` using Google Colab or Jupyter Notebook.

3. Download the phishing website dataset from the original repository.

4. Update the dataset path inside the notebook if necessary.

5. Run all notebook cells from top to bottom.

---

# Project Workflow

The notebook includes:

- Data loading
- Data inspection
- Missing value analysis
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Logistic Regression model
- Random Forest model
- Model evaluation
- Error analysis
- Feature importance analysis

---

# Results Summary

The Random Forest model achieved the best overall performance, outperforming Logistic Regression across all evaluation metrics.

---

# Author

**Tasneem Mrahel**

B.Sc. Computer Science

University of Haifa
