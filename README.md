
# Iris Species Classification with Random Forest

![Iris Flowers](https://upload.wikimedia.org/wikipedia/commons/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg)

## 🎯 Objective

- Classify Iris flowers into `Setosa`, `Versicolor`, and `Virginica`.
- Visualize feature distributions and correlations.
- Reduce dimensionality using **PCA**.
- Evaluate model performance using accuracy, confusion matrix, and classification report.

---

## 📊 Dataset Overview

- File: `IRIS.csv`
- Features:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- Target:
  - `species` (Setosa, Versicolor, Virginica)

---

## 📦 Key Features

| Feature | Description |
|--------|-------------|
| ✅ Classification | Using **Random Forest** with `scikit-learn` |
| 📉 PCA Analysis | Visualize data in 2D space |
| 📊 Confusion Matrix | Visual evaluation of model predictions |
| 🎻 Violin Plots | Feature distribution per class |
| 🐝 Swarmplots | Individual sample spread |
| 📦 Boxplots | Outlier and central tendency visualization |
| 🔥 Correlation Heatmap | Feature-to-feature correlation matrix |
| 🌈 Pairplot | KDE and pairwise scatter comparison |

---

## 🧠 ML Workflow

1. **Load Data** – Load from CSV using `pandas`
2. **Train-Test Split** – 80% training and 20% testing
3. **Modeling** – Use `RandomForestClassifier`
4. **Evaluation** – Accuracy, confusion matrix, classification report
5. **Visualization** – Deep feature analysis with multiple plots
6. **PCA** – Reduce to 2D for better understanding of spread

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (for ML and PCA)

---

## 📂 Project Structure

Iris-Flower-Classification/ ├── iris_classification.ipynb ├── data/ │ └── IRIS.csv ├── README.md └── requirements.txt


---

## 📈 Model Results (Sample Run)

| Metric | Value |
|--------|-------|
| ✅ Accuracy | ~96.67% |
| 📊 Confusion Matrix | 3x3 with minimal misclassifications |
| 🧾 Classification Report | High precision & recall across classes |

---

## 🖼️ Visualizations Included

- ✅ Confusion Matrix Heatmap
- ✅ Violin Plots
- ✅ Swarm Plots
- ✅ Box Plots
- ✅ Pairplot with KDE
- ✅ PCA 2D Scatter Plot
- ✅ Correlation Heatmap

---

## 📌 Usage

1. Open the notebook in **Jupyter Notebook via VS Code**
2. Install dependencies via `requirements.txt`
3. Run all cells for preprocessing, training, and visualization

---


