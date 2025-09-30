# Task 6: K-Nearest Neighbors (KNN) Classification

## 📌 Objective
Implement the KNN algorithm for classification, experiment with different values of K, and visualize results.

## 📊 Dataset
- **Iris Dataset** from `sklearn.datasets`
- Features: Sepal length, Sepal width, Petal length, Petal width
- Classes: Setosa, Versicolor, Virginica

## ⚙️ Steps Performed
1. Loaded the Iris dataset.
2. Normalized features using `StandardScaler`.
3. Split dataset into training and testing sets.
4. Implemented **KNN classifier** with different values of K.
5. Selected the best K based on accuracy.
6. Evaluated the model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
7. Visualized:
   - Accuracy vs K plot
   - Confusion matrix heatmap
   - Decision boundaries (using petal length & width)

## 📈 Results
- Best K value: *Varies depending on random split (commonly K=3 or 5)*.
- Achieved accuracy: ~95–100% on test data.
- Clear separation between classes in decision boundary visualization.

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📤 Submission
Push the following into your GitHub repository:
- `KNN_Classification_Task6.ipynb` (Google Colab notebook)
- `README.md`
- Screenshots (optional)

Then, submit your repo link using the given Google Form.
