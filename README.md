# Belajar Machine Learning untuk Pemula (BMLP) - Final Submission

This repository contains my final project submission for the **Belajar Machine Learning untuk Pemula (BMLP)** course. The project demonstrates an end-to-end machine learning workflow using a bank transaction dataset, including both **unsupervised learning (clustering)** and **supervised learning (classification)**.

## 📌 Project Overview

The project consists of two main stages:

1. **Clustering**
   - Perform exploratory data analysis (EDA).
   - Clean and preprocess the dataset.
   - Apply feature encoding and scaling.
   - Build a K-Means clustering model.
   - Interpret and analyze the resulting clusters.

2. **Classification**
   - Use the generated cluster labels as the target variable.
   - Train a Decision Tree classifier.
   - Evaluate model performance using standard classification metrics.
   - Explore additional models and hyperparameter tuning for improved performance.

## 📊 Dataset

The dataset contains synthetic bank transaction records, including:
- Transaction amount
- Transaction type
- Customer age
- Customer occupation
- Transaction duration
- Login attempts
- Account balance
- Transaction channel
- Customer location

Identifier and timestamp columns are excluded during preprocessing to improve model quality.

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Yellowbrick
- Joblib
- Jupyter Notebook

## 📂 Repository Structure

```text
├── [Clustering]_Submission_Akhir_BMLP_Aldyth_Nahak.ipynb
├── [Klasifikasi]_Submission_Akhir_BMLP_Aldyth_Nahak.ipynb
├── model_clustering.h5
├── PCA_model_clustering.h5
├── decision_tree_model.h5
├── explore_random_forest_classification.h5
├── tuning_classification.h5
├── data_clustering.csv
├── data_clustering_inverse.csv
├── bank_transactions_data.csv
├── requirements.txt
└── README.md
```

## 🚀 Running the Project

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/BMLP-Aldyth-Nahak.git
cd BMLP-Aldyth-Nahak
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Execute the notebooks in the following order:
   1. `[Clustering]_Submission_Akhir_BMLP_Aldyth_Nahak.ipynb`
   2. `[Klasifikasi]_Submission_Akhir_BMLP_Aldyth_Nahak.ipynb`

## 📈 Machine Learning Models

### Clustering
- K-Means Clustering
- PCA (optional) for visualization and dimensionality reduction

### Classification
- Decision Tree Classifier
- Additional model exploration (optional)
- Hyperparameter tuning (optional)

## 🎯 Objective

The goal of this project is to identify meaningful patterns in bank transaction data through clustering and then build a classification model capable of predicting the generated cluster labels.

## 📄 Course Information

- **Course:** Belajar Machine Learning untuk Pemula (BMLP)
- **Platform:** Dicoding Indonesia
- **Author:** Aldyth Nahak