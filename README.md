# Phishing Website Detection using Machine Learning

## Project Description

This project was developed as part of the **Data Science in Cybersecurity** course at the **University of Haifa**.

The objective of this project is to reproduce and critically evaluate a published phishing website detection study using machine learning techniques. The project follows a complete machine learning pipeline, including data exploration, preprocessing, feature engineering, model training, evaluation, and error analysis.

Two supervised machine learning models were implemented and compared:

- Logistic Regression
- Random Forest

The implementation was developed using **Python** in **Google Colab**.

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
├── phishing_detection.ipynb
├── report.pdf
├── README.md
```

---

## Project Workflow

The notebook includes the following stages:

- Data loading and inspection
- Missing value analysis
- Duplicate analysis
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Logistic Regression
- Random Forest
- Model Evaluation
- Error Analysis
- Feature Importance Analysis

---

## Results Summary

Both machine learning models achieved strong performance in detecting phishing websites.

The **Random Forest** model obtained the best overall results, outperforming Logistic Regression across the evaluation metrics used in this project.

---

## Requirements

Python **3.10** or newer.

Required Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install all required packages using:

```bash
pip install -r requirements.txt
```

or

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Execution Instructions

1. Clone this repository.

```bash
git clone https://github.com/Mrahelm/phishing-website-detection.git
```

2. Open **phishing_detection.ipynb** using **Google Colab** or **Jupyter Notebook**.

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
