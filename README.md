# Breast Cancer ML Diagnosis

This project investigates how machine learning models can be used to predict breast cancer diagnosis using the Breast Cancer Wisconsin dataset.

The main goal of the project is to evaluate how reliable machine learning models remain when only a limited number of tumour measurement features are available.

---

# Project Goal

Many studies using the Wisconsin dataset focus on improving classification accuracy or comparing algorithms.

This project investigates whether machine learning models can still make reliable predictions when fewer tumour measurements are available.

The study evaluates model performance when using:

- All diagnostic features
- The five most important features
- The three most important features

---

# Dataset

The dataset used in this project is the **Breast Cancer Wisconsin (Original) dataset**.

Source:

https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original)

Dataset characteristics:

- -699 patient samples
- 9 tumour measurement features
- binary classification target (benign or malignant)

The measurements are derived from **fine needle aspiration (FNA)** of breast tissue.

---

# Methods

The project includes several stages of analysis:

- Exploratory Data Analysis (EDA)
- Statistical analysis
- Correlation analysis
- Principal Component Analysis (PCA)
- Machine learning classification models

Models used:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

Feature reduction experiments are performed to analyse model reliability when diagnostic information is limited.

---

# Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Cross-validation is used to ensure reliable performance estimates.

---

# Repository Structure

breast-cancer-ml-diagnosis
│
├── data
│   ├── raw
│   │   └── breast-cancer-wisconsin.data
│   └── processed
│
├── notebooks
│   ├── 01_eda.ipynb
│   ├── 02_eda_statistical_analysis.ipynb
│   ├── 03_pca_analysis.ipynb
│   ├── 04_model_training.ipynb
│   └── 05_feature_reduction_experiments.ipynb
│
├── results
│   └── figures
│
├── README.md
├── requirements.txt
└── LICENSE

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

# Getting Started

Clone the repository:

git clone https://github.com/killianharnett1/breast-cancer-ml-diagnosis.git

Move into the project folder:

cd breast-cancer-ml-diagnosis

Install required packages:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Start with the EDA notebook inside the notebooks folder.

---

# Project Contribution

The key contribution of this research is evaluating how reliable machine learning models remain when diagnostic information is limited.

instead of only focusing on accuracy the project investigates how model performance changes when fewer tumour measurements are available.

This provides insight into the practical use of machine learning for medical diagnosis when complete diagnostic information is not always available.
