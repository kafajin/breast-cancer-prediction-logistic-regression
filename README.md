# Breast Cancer Prediction using Logistic Regression (from Scratch)

## 🧠 Introduction
Breast cancer is one of the most common and serious diseases affecting women worldwide. Early and accurate detection is crucial, as it can significantly improve treatment outcomes and save lives.

The goal of this project is to build a **binary classification model** that predicts whether a breast tumor is **Malignant (M)** or **Benign (B)** based on diagnostic measurements.

To strengthen the understanding of machine learning fundamentals, **Logistic Regression is implemented from scratch**, without using high-level machine learning libraries.

---

## 📊 Dataset
This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which contains:
- **569 samples**
- **30 numerical features** describing characteristics of cell nuclei
- **Target variable:** Diagnosis (Malignant or Benign)

The dataset is publicly available on Kaggle.

---

## ⚙️ Methodology
The project follows these main steps:
- Data loading and preprocessing  
- Feature normalization  
- Logistic Regression formulation  
- Implementation of gradient descent  
- Model training and evaluation  

Logistic Regression is chosen because it is:
- Interpretable  
- Computationally efficient  
- A strong baseline for medical classification tasks  

---

## 📈 Results
The Logistic Regression model demonstrates strong performance on the Breast Cancer Wisconsin (Diagnostic) dataset.

- **Accuracy:** 99.12%  
- **F1-score:** 0.99  

The classification report shows consistently high precision and recall for both malignant and benign classes, indicating that the model effectively balances false positives and false negatives.

These results suggest that a well-implemented Logistic Regression model can achieve excellent performance on this medical classification task.

Note: The high performance is expected due to the relatively clean and well-structured nature of the dataset.

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Kaggle Notebooks  

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/kafajin/breast-cancer-prediction-logistic-regression.git
Open the notebook:

breast_cancer_logistic_regression_from_scratch.ipynb
Run all cells in order.

## 🎯 Key Takeaways
- Gained a deeper understanding of Logistic Regression mechanics

- Implemented gradient descent from first principles

- Worked with a real-world medical dataset

- Practiced structuring a professional machine learning project

## 📌 Project Context
This project was developed as part of a Machine Learning course assignment.

The work was carried out collaboratively by two students, focusing on understanding and implementing Logistic Regression from scratch using a real-world medical dataset.
