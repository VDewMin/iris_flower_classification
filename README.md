# Iris Flower Classification 🌸

## 📌 Project Description
This project implements a supervised machine learning model to classify iris
flowers into three species — Setosa, Versicolor, and Virginica — based on four
numerical features.

The project is based on concepts learned from the *Supervised Machine Learning*
course by Dr. Andrew Ng and is intended as a beginner-friendly demonstration of
a complete ML workflow.

---

## 📊 Dataset
- Source: `sklearn.datasets.load_iris`
- Samples: 150
- Features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- Classes: 3 (balanced)

---

## 🧠 Model Used
**Logistic Regression**
- Suitable for multi-class classification
- Interpretable and efficient
- Performs well on linearly separable datasets

---

## ⚙️ Workflow
1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Train-test split
4. Model training
5. Model evaluation using:
   - Accuracy
   - Confusion matrix
   - Precision, recall, F1-score
6. Feature coefficient interpretation

---

## 📈 Results
- High overall accuracy on the test set
- Excellent classification of Setosa
- Minor confusion between Versicolor and Virginica
- Balanced precision and recall across classes

---

## 🔍 Limitations & Future Work
- Apply feature scaling
- Use cross-validation for more robust evaluation
- Compare Logistic Regression with other classifiers

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🎓 Learning Outcome
This project reinforces fundamental machine learning concepts including data
exploration, supervised learning, model evaluation, and interpretability.
