# Machine Learning Project for Adult Income data

---

## 📌 Overview

Adult Income prediction using machine learning classification models, preprocessing, model tuning, and evaluation.

---

## 📊 about Dataset 

* Number of Columns : 15
* Number of Rows : 32537
* Number of Duplicates : 24
* Number of Nan Values : 0
* Columns : [age, workclass, fnlwgt, education, education.num, marital.status, occupation, relationship, race, sex, capital.gain, capital.loss, hours.per.week, native.country, income]
* Columns That Don`t Matter : [fnlwdt]
* Target : income
* Classification Problem


---

## Why Delete Columns That Don`t Matter?
Because There Are Extra Information And It Doesn`t Affect The Target

---

## 🧠 Models
Models Used :

* Random Forest 
* XGBoost 
* LightGBM
* Gradient Boosting

---

## ⚙️ Preprocessing

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Scaling
* Missing Value Imputation
* Hyperparameter Tuning
* Model Evaluation
* Evaluation Metrics

---

## 🛠️ Technologies

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* LightGBM
* Joblib

---

## 📊 Model Evaluation
- The model Evaluated by Accuracy, F1, Precision, Recall, roc_auc

---

## 📈 Results


| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
| :--- | ---: | ---: | ---: | ---: | ---: |
| Random Forest | 86.29% | 75.03% | 61.90% | 67.84% | 91.64% |
| XGBoost | 87.32% | 76.06% | 66.71% | 71.08% | 92.64% |
| LightGBM | 87.43% | 76.71% | 66.31% | 71.13% | 92.73% |
| Gradien Boosting | 87.27% | 76.37% | 65.92% | 70.76% | 92.60% |

---

## 📂 Project Structure

```text
.
├── data/
├── images/
├── models/
├── .gitignore
├── Adult.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Install requirements :
```text

pip install -r requirements.txt

```
then run ipynb file
