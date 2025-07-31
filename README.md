# 🌸 Iris Flower Classification – Machine Learning Project

This is a beginner-friendly **Supervised Machine Learning** project using the famous **Iris dataset**.  
The goal is to build a model that can predict the species of an Iris flower using its **sepal** and **petal** measurements.

---

## 📌 Project Type

- **Type**: Supervised Machine Learning
- **Task**: Classification
- **Model Used**: K-Nearest Neighbors (KNN)
- **Level**: Beginner

---

## 📂 Dataset Info

The dataset contains **150 samples** of iris flowers and 3 species:

- `Iris setosa`
- `Iris versicolor`
- `Iris virginica`

Each sample has the following **4 features**:

| Feature        | Description               |
|----------------|---------------------------|
| Sepal length   | in cm                     |
| Sepal width    | in cm                     |
| Petal length   | in cm                     |
| Petal width    | in cm                     |

Target label: `species` (setosa / versicolor / virginica)

---

## 🧠 Steps Performed

1. **Import Libraries**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`
2. **Load Dataset** using `sklearn.datasets.load_iris()`
3. **Convert to DataFrame** for easy manipulation
4. **Data Exploration**: `.info()`, `.describe()`, `.head()`
5. **Data Visualization** using `seaborn.pairplot()` to see class separations
6. **Train-Test Split** using `train_test_split()` (80% training, 20% testing)
7. **Model Training** with `KNeighborsClassifier(n_neighbors=3)`
8. **Prediction and Accuracy Score**
9. **Confusion Matrix** to evaluate misclassifications

---

## 🚀 Results

- **Model Accuracy**: ~95% using KNN
- High separation seen in **petal features** during visualization
- Can be improved using SVM, Decision Tree, or tuning parameters

---

## 📎 Requirements

Install these before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
