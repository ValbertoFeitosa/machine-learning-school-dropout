# Machine Learning for School Dropout Prediction

<p align="center">
  <img src="images/banner.png" alt="Machine Learning for School Dropout Prediction">
</p>

## Overview

This project presents a Machine Learning approach for predicting student failure in first-semester Mathematics as an early indicator of school dropout risk.

Using historical academic records from the Federal Institute of Education, Science and Technology of Ceará (IFCE), the project develops predictive classification models capable of supporting early pedagogical interventions and evidence-based educational decision-making.

The project is based on a peer-reviewed scientific publication published in the journal *Research, Society and Development* (2025).

---

## Problem

Academic failure during the first semester is one of the strongest indicators associated with student retention and school dropout.

The objective of this project is to identify students at higher risk of failure before academic problems become more difficult to reverse.

---

## Dataset

The dataset contains historical academic records from IFCE – Fortaleza Campus.

Main characteristics:

- 468 complete student records
- Six integrated technical programs
- Admission cohorts from 2018 to 2020
- Anonymous educational data
- Binary classification:
  - Pass
  - Fail

---

## Machine Learning Pipeline

The complete workflow includes:

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- One-Hot Encoding
- SMOTE (Class Balancing)
- Feature Selection (SelectKBest)
- Model Training
- Model Evaluation

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SMOTE
- Jupyter Notebook

---

## Machine Learning Models

The following supervised learning algorithms were evaluated:

- Logistic Regression
- Gaussian Naive Bayes

Performance was assessed using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Cross Validation

---

## Results

The best-performing model was **Logistic Regression**.

| Metric | Value |
|---------|-------|
| Accuracy | 0.73 |
| ROC-AUC | 0.77 |
| Cross Validation | 0.68 |
| Recall (Risk Class) | 0.79 |

These results demonstrate that Machine Learning can support early identification of students at risk of academic failure and contribute to educational decision-making.

---

## Repository Structure

```
machine-learning-school-dropout/

├── data/
├── notebooks/
├── src/
├── models/
├── images/
├── paper/
├── results/
├── README.md
└── requirements.txt
```

---

## Scientific Publication

This repository is based on the peer-reviewed paper:

**Machine Learning: An Application for School Dropout Prevention**

Research, Society and Development

Volume 14, Issue 6, 2025

DOI:
https://doi.org/10.33448/rsd-v14i6.49029

---

## Citation

If you use this work, please cite:

Pereira, V. R. F., Romeu, M. C., Freitas, N. C., & Pereira, V. S. (2025). *Machine Learning: An Application for School Dropout Prevention*. Research, Society and Development.

---

## Author

**Valberto Feitosa**

Data Scientist • Applied Statistics • Machine Learning • Educational Analytics

GitHub:
https://github.com/ValbertoFeitosa

LinkedIn:
https://www.linkedin.com/in/valberto-feitosa-7239511b1/

---

## License

This project is released under the MIT License.
