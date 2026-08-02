# 🎓 Machine Learning for School Dropout Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success)
![Educational Analytics](https://img.shields.io/badge/Educational-Analytics-0066cc)
![License](https://img.shields.io/badge/License-MIT-green)
![Research](https://img.shields.io/badge/Peer--Reviewed-Research-blueviolet)

<p align="center">
  <img src="images/banner-project.jpeg" alt="Machine Learning for School Dropout Prediction" width="100%">
</p>

---

# Overview

This repository presents a Machine Learning solution for predicting student failure in first-semester Mathematics as an early indicator of school dropout risk.

The project applies data preprocessing, class balancing, feature selection and supervised learning algorithms to identify students at higher risk, supporting early educational interventions and evidence-based decision making.

This work is based on a peer-reviewed scientific publication published in the journal **Research, Society and Development (2025)**.

---

# Table of Contents

- Overview
- Problem
- Objectives
- Dataset
- Machine Learning Pipeline
- Technologies
- Machine Learning Models
- Results
- Repository Structure
- How to Run
- Scientific Publication
- Citation
- Future Improvements
- Author
- License

---

# Problem

School dropout is one of the main challenges faced by educational institutions.

Research has shown that poor academic performance during the first semester is one of the strongest indicators associated with future dropout.

This project aims to identify students at risk before academic difficulties become irreversible.

---

# Objectives

- Predict student failure in first-semester Mathematics.
- Support early pedagogical interventions.
- Compare supervised Machine Learning algorithms.
- Evaluate predictive performance using statistical metrics.
- Demonstrate the application of Educational Data Mining techniques.

---

# Dataset

The dataset contains anonymized historical academic records from the Federal Institute of Education, Science and Technology of Ceará (IFCE).

### Characteristics

- 468 student records
- Six technical education programs
- Admission years from 2018 to 2020
- Anonymous educational data
- Binary classification

Target variable:

- ✅ Pass
- ❌ Fail

---

# Machine Learning Pipeline

The complete workflow includes:

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. One-Hot Encoding
6. Class Balancing (SMOTE)
7. Feature Selection (SelectKBest)
8. Model Training
9. Cross Validation
10. Model Evaluation

---

# Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib
- Jupyter Notebook

---

# Machine Learning Models

The following supervised learning algorithms were evaluated:

- Logistic Regression
- Gaussian Naive Bayes

Performance evaluation considered:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Cross Validation

---

# Results

The best-performing model was **Logistic Regression**.

| Metric | Value |
|---------|-------:|
| Accuracy | 0.73 |
| ROC-AUC | 0.77 |
| Cross Validation | 0.68 |
| Recall | 0.79 |

These results demonstrate that Machine Learning techniques can effectively support early identification of students at risk of academic failure and school dropout.

---

# Repository Structure

```
machine-learning-school-dropout/

│
├── data/
│
├── images/
│   ├── banner-project.jpeg
│
├── models/
│
├── notebooks/
│
├── paper/
│   └── article.pdf
│
├── results/
│
├── src/
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

---

# How to Run

Clone the repository

```bash
git clone https://github.com/ValbertoFeitosa/machine-learning-school-dropout.git
```

Enter the project directory

```bash
cd machine-learning-school-dropout
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# Scientific Publication

This repository is based on the following peer-reviewed paper:

**Machine Learning: An Application for School Dropout Prevention**

Research, Society and Development

Volume 14, Issue 6 (2025)

DOI:

https://doi.org/10.33448/rsd-v14i6.49029

---

# Citation

If you use this repository in your research, please cite:

```bibtex
@article{Pereira2025,
  title={Machine Learning: An Application for School Dropout Prevention},
  author={Pereira, Valberto Rômulo Feitosa and collaborators},
  journal={Research, Society and Development},
  volume={14},
  number={6},
  year={2025},
  doi={10.33448/rsd-v14i6.49029}
}
```

---

# Future Improvements

- Add new Machine Learning algorithms
- Hyperparameter optimization
- Explainable AI (SHAP/LIME)
- Deep Learning models
- Deployment using FastAPI
- Interactive dashboard
- Cloud deployment

---

# Author

## Valberto Feitosa

**Data Scientist | Applied Statistics | Machine Learning | Educational Analytics**

Professor and Researcher at the Federal Institute of Education, Science and Technology of Ceará (IFCE).

- GitHub: https://github.com/ValbertoFeitosa
- LinkedIn: https://www.linkedin.com/in/valberto-feitosa-7239511b1/

---

# License

This project is distributed under the **MIT License**.
