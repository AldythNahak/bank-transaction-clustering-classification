# Bank Transaction Clustering & Classification

A machine learning project that analyzes synthetic bank transaction data using both **unsupervised learning** and **supervised learning** techniques. The project was developed as part of the final submission for the *Belajar Machine Learning untuk Pemula (BMLP)* course.

## 📌 Project Overview

The objective of this project is to:
1. Discover hidden patterns in customer transaction behavior using **K-Means Clustering**.
2. Interpret and analyze the resulting customer segments.
3. Build a **Decision Tree Classification** model capable of predicting the generated cluster labels.

The workflow combines data preprocessing, exploratory data analysis, clustering, cluster interpretation, and classification into a complete end-to-end machine learning pipeline.

## 📊 Dataset

The dataset contains anonymized bank transaction records with information such as:
- Transaction amount
- Transaction type
- Customer age
- Customer occupation
- Account balance
- Transaction duration
- Login attempts
- Transaction channel
- Customer location

Several identifier and timestamp columns are removed during preprocessing to improve model quality.

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Yellowbrick
- Joblib
- Jupyter Notebook

## 🔄 Project Workflow

```text
Raw Dataset
     │
     ▼
Exploratory Data Analysis (EDA)
     │
     ▼
Data Cleaning & Preprocessing
     │
     ├── Missing Value Handling
     ├── Duplicate Removal
     ├── Label Encoding
     ├── Outlier Treatment
     └── Feature Scaling
     │
     ▼
K-Means Clustering
     │
     ├── Elbow Method
     ├── Silhouette Score Evaluation
     └── PCA Visualization
     │
     ▼
Cluster Interpretation
     │
     ▼
Generate Target Labels
     │
     ▼
Decision Tree Classification
     │
     ▼
Model Evaluation & Comparison
```

## 📂 Repository Structure

```text
├── data/          # Raw and processed datasets
├── notebooks/     # Clustering and classification notebooks
├── models/        # Saved machine learning models
├── images/        # Figures and visualizations
├── requirements.txt
└── README.md
```

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/<your-username>/bank-transaction-clustering-classification.git
cd bank-transaction-clustering-classification
```

2. Create and activate a virtual environment (optional):

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```powershell
.venv\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the notebooks in the following order:
   - `notebooks/[Clustering]_Submission_Akhir_BMLP_Aldyth_Nahak.ipynb`
   - `notebooks/[Klasifikasi]_Submission_Akhir_BMLP_Aldyth_Nahak.ipynb`

## 📈 Models

### Unsupervised Learning
- K-Means Clustering
- PCA for visualization and dimensionality reduction

### Supervised Learning
- Decision Tree Classifier
- Additional model comparison (optional enhancement)
- Hyperparameter tuning

## 🎯 Results

The project identifies meaningful customer transaction clusters and uses them as labels for a supervised classification task. Model performance is evaluated using standard classification metrics, including accuracy, precision, recall, and F1-score.

## 📄 License

This project is intended for educational and portfolio purposes.

---

**Author:** Aldyth Nahak  
**Course:** Belajar Machine Learning untuk Pemula (BMLP)  
**Tools:** Python, Scikit-learn, Jupyter Notebook
