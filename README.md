# PCA-Dimensionality-Reduction-Handwritten-Digits
# 🔢 PCA Dimensionality Reduction - Handwritten Digits Dataset

## 📌 Project Overview
This project demonstrates the use of **Principal Component Analysis (PCA)** for reducing the dimensionality of the **scikit-learn digits dataset** from 64 features to 2 features, enabling easy visualization of digit clusters.

## 📊 Dataset
- **Source:** `load_digits()` from scikit-learn
- **Images:** 8x8 grayscale images of handwritten digits (0-9)
- **Total Samples:** 1797
- **Original Feature Dimension:** 64

## 🚀 Steps Performed
1. Loaded the digits dataset from sklearn.datasets
2. Applied PCA to reduce 64 features to 2 dimensions
3. Visualized digit clusters in a **2D scatter plot** colored by digit labels
4. Displayed the **explained variance ratio** for each principal component
5. Plotted **cumulative variance** to determine the number of components needed for 95% variance

## 🛠 Technologies Used
- Python
- scikit-learn
- Matplotlib
- Seaborn

## 📈 Output
- **Original Data Shape:** (1797, 64)
- **Reduced Data Shape:** (1797, 2)
- **2D Scatter Plot:** Digits represented in reduced space
- **Explained Variance Ratios**
- **Cumulative Variance Plot** with 95% threshold line

## 🔧 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/PCA-Dimensionality-Reduction-Handwritten-Digits.git
cd PCA-Dimensionality-Reduction-Handwritten-Digits

# Install dependencies
pip install scikit-learn matplotlib seaborn

# Run Jupyter Notebook
jupyter notebook pca_digits.ipynb
