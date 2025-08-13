# Principal Component Analysis (PCA) – Dimensionality Reduction Examples

## 📌 Overview
This repository demonstrates the use of *Principal Component Analysis (PCA)* to reduce the dimensionality of datasets before applying machine learning models.  
Both examples use *Logistic Regression* to classify handwritten digits after transforming features with PCA:
1. *95% Variance Retained* – Automatically selects the number of components that retain 95% of the dataset’s information.
2. *2 Components Only* – Reduces the dataset to 2 principal components for visualization and analysis.

## 📖 About PCA
PCA is a *linear dimensionality reduction* technique that projects data into a lower-dimensional space while preserving as much variance as possible.  
- It uses *orthogonal transformations* to create uncorrelated principal components.
- Useful for *noise reduction, **faster model training, and **visualization* in 2D or 3D.

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ PCA with 95% Variance Retained
- Automatically determines the number of components needed to retain 95% of data variance.
- Logistic Regression is trained on the reduced dataset for classification.

### 2️⃣ PCA with 2 Components
- Forces dimensionality to 2 components for visualization purposes.
- Allows plotting of decision boundaries and cluster separation.
