# Task 6: K-Nearest Neighbors (KNN) Classification  

This repository contains my implementation of **K-Nearest Neighbors (KNN)** for classification, as part of the AI & ML Internship tasks.  

---

## 📌 Objective
To understand and implement the **KNN algorithm** for classification problems using **Scikit-learn** and visualize how the algorithm performs with different values of *K*.  

---

## 📊 Dataset
- **Iris Dataset** (from `sklearn.datasets`)  
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width  
- Target: Iris species (Setosa, Versicolor, Virginica)  

---

## ⚙️ Steps Performed
1. **Data Loading** – Imported the Iris dataset.  
2. **Normalization** – Scaled features using `StandardScaler` to ensure fair distance measurement.  
3. **Train-Test Split** – Divided data into training and testing sets.  
4. **Model Building** – Applied `KNeighborsClassifier` from `sklearn.neighbors`.  
5. **Experimentation with K** – Tested multiple values of K to find the best performance.  
6. **Evaluation** – Used:
   - **Accuracy Score**  
   - **Confusion Matrix**  
7. **Visualization** – Plotted decision boundaries and accuracy vs. K graph.  

---

## 📈 Results
- Best accuracy achieved at **K = X** (replace X with your observed best K).  
- Accuracy on test set: **YY%** (replace with your value).  
- Decision boundary visualization shows clear separation between classes.  

---

## 📌 Key Learnings
- **Normalization is crucial** for distance-based algorithms like KNN.  
- The choice of **K value impacts bias-variance trade-off**.  
- KNN is simple but can be computationally expensive on large datasets.  

---

## 📚 Interview Questions Covered
- How does the KNN algorithm work?  
- How do you choose the right K?  
- Why is normalization important in KNN?  
- What is the time complexity of KNN?  
- Pros and cons of KNN  
- Sensitivity to noise  
- Handling multi-class problems  
- Role of distance metrics in KNN  

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 🚀 How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/gnishitha2004-source/AI-ML-Internship-Task6.git
   cd AI-ML-Internship-Task6
