# Rock vs Mine Prediction (Sonar Dataset)

## 📌 Project Overview

This project predicts whether an object detected by sonar is a **Rock** or a **Mine** using machine learning. The model is trained on the **Sonar Dataset**, which contains 60 numerical features representing sonar signal returns.

This notebook includes:

* Data loading and exploration
* Train/test splitting
* Logistic Regression model training
* Model evaluation
* Predictive system for new inputs

---

## 📂 Dataset

The dataset used is the **Sonar Mines vs Rocks** dataset from the UCI Machine Learning Repository.

Each row has:

* **60 input features**: Energy values from sonar returns
* **1 output label**: `R` (Rock) or `M` (Mine)

---

## 🚀 Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn (Logistic Regression)
* Jupyter Notebook

---

## 🧠 Model Used

### **Logistic Regression**

Chosen because:

* Works well for binary classification
* Fast and interpretable
* Performs well on smaller datasets

---

## 📊 Results

The model achieves high accuracy on both training and test datasets.

Evaluation metrics include:

* Accuracy score
* Predictions on sample data

---

## ▶️ How to Run

1. Clone the repository or download the notebook.
2. Install required libraries:

```bash
pip install numpy pandas scikit-learn
```

3. Open the notebook:

```bash
jupyter notebook Rock_vs_Mine_Prediction.ipynb
```

4. Run all cells.

---

## 🏁 Conclusion

The project demonstrates how machine learning can classify sonar signals effectively using Logistic Regression. It serves as a solid beginner-level ML classification project.

---

## 📎 Author

**Sarthak Mahajan**

Feel free to use or modify the project! 🎯
