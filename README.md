# Task 6: K-Nearest Neighbors (KNN) Classification

## 📌 Objective

Implement and understand the **K-Nearest Neighbors (KNN)** algorithm for classification tasks.

This project demonstrates how KNN works using the **Iris dataset**, covering data preprocessing, model training, evaluation, and visualization.

---

## 🛠 Tools & Libraries

* **Python 3**
* **Pandas** – data handling
* **NumPy** – numerical operations
* **Scikit-learn** – machine learning models & evaluation
* **Matplotlib / Seaborn** – data visualization

---

## 📂 Dataset

* **Dataset used**: [Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
* Features: Sepal length, Sepal width, Petal length, Petal width
* Target: Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Steps Performed

1. **Data Preprocessing**

   * Loaded the Iris dataset
   * Normalized feature values for better distance-based performance

2. **Model Building**

   * Implemented KNN using `KNeighborsClassifier` from scikit-learn
   * Experimented with different values of *K*

3. **Evaluation**

   * Accuracy score
   * Confusion Matrix

4. **Visualization**

   * Plots for accuracy with different *K* values
   * Decision boundary visualization

---

## 📊 Results

| K Value | Accuracy |
| ------- | -------- |
| 3       | 96%      |
| 5       | 97%      |
| 7       | 96%      |

* Best performance achieved at **K = 5**.
* Confusion matrix showed correct classification with very few misclassifications.

---

## 📈 Visualizations

* Accuracy vs K plot
* Decision boundary plots (Setosa, Versicolor, Virginica clearly separated)

---

## 🧠 Interview Questions & Answers

**1. How does the KNN algorithm work?**
KNN classifies a new data point based on the majority class among its *k* nearest neighbors using a distance metric (e.g., Euclidean).

**2. How do you choose the right K?**
Experiment with different K values and select the one that gives the best accuracy on validation data. Odd values are preferred to avoid ties.

**3. Why is normalization important in KNN?**
Because KNN relies on distance, features with larger scales may dominate. Normalization ensures all features contribute equally.

**4. What is the time complexity of KNN?**

* Training: **O(1)** (instance-based, no explicit training)
* Prediction: **O(N × d)**, where *N* = number of training samples and *d* = number of features

**5. Pros & Cons of KNN**

* ✅ Simple, effective, no training phase
* ❌ Slow for large datasets, sensitive to noise, requires feature scaling

**6. Is KNN sensitive to noise?**
Yes, noisy points or outliers can mislead classification since KNN is instance-based.

**7. How does KNN handle multi-class problems?**
By majority voting across all classes among nearest neighbors.

**8. What’s the role of distance metrics in KNN?**
Defines how “closeness” is measured. Common metrics: Euclidean, Manhattan, Minkowski.

---

## ✅ Conclusion

* KNN works best on normalized data.
* Optimal K value for the Iris dataset was **K = 5**.
* It is a simple yet powerful algorithm for small to medium-sized datasets.

---

## 📎 References

* [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
* [Iris Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/iris)
