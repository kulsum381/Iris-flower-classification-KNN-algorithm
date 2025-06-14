# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

This project demonstrates a simple machine learning application using the **Iris flower dataset** to classify flower species based on their physical attributes. The algorithm used is **K-Nearest Neighbors (KNN)**.

---

## 📌 Objective

To predict the species of an Iris flower (*Setosa*, *Versicolor*, *Virginica*) using its:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 📂 Dataset

- Built-in **Iris dataset** from `sklearn.datasets`
- 150 samples, 3 classes (species), 4 features

---

## 🛠 Tools & Libraries

- **Python**
- **Google Colab / Jupyter Notebook**
- Libraries:
  - `pandas`
  - `sklearn`
  - `matplotlib` (optional for visualization)
  - `seaborn` (optional for EDA)

---

## 🧠 Algorithm Used

- **K-Nearest Neighbors (KNN)**
- Initially used **k = 3**; can be tuned for better performance

---

## 🔍 Steps Involved

1. Load the Iris dataset using `sklearn.datasets`
2. Convert it to a `pandas.DataFrame`
3. Perform exploratory data analysis (optional)
4. Split data into **training** and **testing** sets
5. Apply **KNN Classifier**
6. Train the model and make predictions
7. Evaluate the model using **accuracy score**
8. Display actual vs predicted values

---

## 📈 Accuracy

The model achieved an accuracy of over **95%** on the test set using `k = 3`.

---

## 📊 Output Sample

![image](https://github.com/user-attachments/assets/c1b54f26-0136-4e25-a984-94f083e75ae8)
