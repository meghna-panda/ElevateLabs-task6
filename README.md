# ElevateLabs-task6
# KNN Classification on Iris Dataset
This project implements the **K-Nearest Neighbors (KNN)** classification algorithm on the Iris dataset using Python and scikit-learn in Google Colab. The aim is to classify iris flowers into one of three species based on flower measurements.

# What’s Done
- **Data Upload**: Loaded the Iris dataset from a local CSV file using `files.upload()` in Colab.
- **Preprocessing**:
  - Removed unnecessary `Id` column.
  - Encoded `Species` labels into numeric format.
  - Normalized features using `StandardScaler`.
- **Modeling**:
  - Split dataset into training (70%) and testing (30%) sets.
  - Trained **KNN models** for various values of K (1, 3, 5, 7, 9).
  - Evaluated each model using **accuracy score** and **confusion matrix**.
- **Visualization**:
  - Plotted **decision boundaries** using the first two features.
  - Visualized class regions for a better understanding of model behavior.

# Dataset
- **Name**: Iris Dataset
- **Source**: UCI Machine Learning Repository
- **Features**: Sepal length, Sepal width, Petal length, Petal width
- **Target**: Species (Setosa, Versicolor, Virginica)

## Files
- `t6_knn.py`: Python script implementing the KNN algorithm.
- `Iris.csv`: Dataset file (uploaded manually in Google Colab).

## Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `sklearn` (for KNN, preprocessing, metrics, and visualization)
