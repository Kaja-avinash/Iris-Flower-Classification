
# Iris Species Classification with Random Forest

![Iris Flowers](https://upload.wikimedia.org/wikipedia/commons/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg)

This project classifies iris flowers into three species using a Random Forest classifier, achieving 100% accuracy.

## 📋 Table of Contents
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualizations](#visualizations)
- [License](#license)

## 🌸 Dataset
The Iris dataset contains measurements for 150 iris flowers from three species:
- Iris-setosa
- Iris-versicolor  
- Iris-virginica

Features:
- Sepal length (cm)
- Sepal width (cm) 
- Petal length (cm)
- Petal width (cm)

## 💻 Installation
1. Clone the repository:
```bash
git clone https://github.com/Kaja-avinash/iris-classification.git
cd iris-classification

🚀 Usage
To train the model and evaluate its performance, simply run the script:

bash
iris-flower-classifier.ipynb
The script will output the following:
Accuracy of the model
Confusion matrix
Classification report
Additionally, it will generate visualizations of the data distribution and the trained model's predictions.

📊 Results
The Random Forest classifier achieved an impressive 96.67% accuracy on the test data. The classification report includes key performance metrics such as:

Precision: How many selected items are relevant
Recall: How many relevant items are selected
F1-score: The harmonic mean of precision and recall
Evaluation metrics like the confusion matrix will also be displayed to give a deeper understanding of the model's performance.

📈 Visualizations
Several visualizations are included to help analyze the dataset and understand the model's performance:

Violin Plots 🎻

Visualizes the distribution of each feature across different species.

Box Plots 📦

Displays the range, interquartile range, and outliers for each feature.

Swarm Plots 🐝

Shows the distribution of individual data points and their relationship to the species classes.

Pair Plot with KDE 🔍

Displays pairwise relationships between features, enhanced with Kernel Density Estimation (KDE) for better feature distribution visualization.

PCA Plot for Dimensionality Reduction 🔽

Uses Principal Component Analysis (PCA) to reduce the dataset's dimensionality and plot it in a 2D space while preserving variance.

Correlation Heatmap 🌡️

A heatmap of the correlation matrix to help visualize relationships between different features.

These visualizations provide critical insights into the feature relationships and data distribution across species, assisting in the understanding of how the model performs.
