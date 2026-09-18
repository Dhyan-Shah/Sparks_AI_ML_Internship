# 🤖 AI/ML Internship — Sparks To Ideas

**Onsite AI/ML Internship | Sparks To Ideas, Ahmedabad**
**18th May 2026 – 16th June 2026**

---

## 📌 Overview

This repository contains all Jupyter Notebooks, datasets, and implementations from my **30-day onsite AI/ML internship** at **Sparks To Ideas, Ahmedabad**. The internship covered the complete Machine Learning workflow — from data preprocessing and EDA to model training, hyperparameter tuning, evaluation, and visualization — using real-world datasets across healthcare, finance, sports analytics, retail, and education domains.

---

## 🗂️ Repository Structure

```
├── N-1_Numpy_Intro_Dim.ipynb          # NumPy — arrays, dimensions, shapes
├── N-2_Indexing_Slicing.ipynb         # NumPy — indexing, slicing, reversing
├── N-3_dtype_shape_reshape.ipynb      # NumPy — dtype, reshape, type casting
├── N-4_Iterating.ipynb                # NumPy — nditer, ndenumerate, flatten
├── N-5_join_stack_split.ipynb         # NumPy — concatenate, stack, split
├── N-6_Search_Sort.ipynb              # NumPy — where, argsort, searchsorted
├── N-7_Random.ipynb                   # NumPy — rand, randint, seed, shuffle
│
├── Day_1_Pandas.ipynb                 # Pandas — Series, DataFrame, loc/iloc
├── Matplotlib.ipynb                   # Matplotlib — line, bar, scatter, pie
├── Seaborn.ipynb                      # Seaborn — lineplot, barplot, heatmap
│
├── Topic-5_Linear_Regression.ipynb    # Linear & Multiple Linear Regression
├── Topic-7_Multiple_Linear_Reg.ipynb  # Multiple Regression + train/test split
├── Topic-9_Polynomial_Regression.ipynb# Polynomial Regression + degree tuning
├── plynomialregression.ipynb          # Practice — diamonds.csv Poly Regression
│
├── Topic-11_KNN_Classifier.ipynb      # K-Nearest Neighbors Classifier
├── batting_team_knn.ipynb             # KNN — IPL batting team prediction
│
├── ML_Test_All_30_Questions.ipynb     # 30-question ML test (all topics)
│
├── datasets/                          # CSV datasets used
│   ├── diamonds.csv
│   ├── deliveries_1.csv
│   ├── insurance.csv
│   └── ...
│
└── README.md
```

---

## 🧠 Algorithms Covered

### Supervised Learning — Regression
| Algorithm | Key Concept | Dataset |
|---|---|---|
| Linear Regression | y = mx + c | advertising.csv, salary.csv |
| Multiple Linear Regression | y = m₁x₁ + m₂x₂ + ... + c | 50_Startups.csv |
| Polynomial Regression | y = m₂x² + mx + c via PolynomialFeatures | diamonds.csv |

### Supervised Learning — Classification
| Algorithm | Key Concept | Dataset |
|---|---|---|
| Logistic Regression | Sigmoid function, binary/multi-class | Titanic, insurance, HR attrition |
| K-Nearest Neighbors | Euclidean distance, K loop, StandardScaler | Diabetes, IPL deliveries |
| Decision Tree | Gini/Entropy splits, max_depth, plot_tree() | Titanic, wine quality |
| Random Forest | Ensemble of trees, feature importance, CV | Titanic, car pricing |

### Unsupervised Learning
| Algorithm | Key Concept | Dataset |
|---|---|---|
| K-Means Clustering | Elbow method, Silhouette Score, K=5 | Mall_Customers.csv |
| DBSCAN | eps, min_samples, noise points (label=-1) | Mall_Customers.csv |

---

## 📊 Key Results

| Task | Dataset | Model | Metric |
|---|---|---|---|
| Diamond Price Prediction | diamonds.csv (53,940 rows) | Polynomial Regression (degree=2) | **R² = 0.9337** |
| Diabetes Classification | Pima Indians Diabetes | KNN (K=12) | **Accuracy = 79.22%** |
| Titanic Survival | titanic.csv | Random Forest | **Accuracy = 82.12%** |
| Customer Segmentation | Mall_Customers.csv | K-Means (K=5) | **Silhouette = 0.554** |
| Batting Team Prediction | IPL deliveries (1,50,454 rows) | KNN (10 classes) | Accuracy = 18% (inherently hard) |

---

## 🛠️ Tech Stack

```python
Python 3.x
├── NumPy          # Numerical computing
├── Pandas         # Data manipulation
├── Matplotlib     # Visualization
├── Seaborn        # Statistical plots
└── Scikit-learn   # ML algorithms, preprocessing, evaluation
    ├── LinearRegression, LogisticRegression
    ├── PolynomialFeatures, LabelEncoder, StandardScaler
    ├── KNeighborsClassifier, KNeighborsRegressor
    ├── DecisionTreeClassifier, DecisionTreeRegressor
    ├── RandomForestClassifier, RandomForestRegressor
    ├── KMeans, DBSCAN
    ├── train_test_split, cross_val_score
    └── Pipeline, SelectFromModel
```

---

## 🔑 Key Concepts Practiced

- **Train/Test Split** — `test_size=0.2, random_state=42` for reproducible evaluation
- **Data Leakage Prevention** — `poly.fit_transform(X_train)` + `poly.transform(X_test)` only
- **Feature Scaling** — `StandardScaler` mandatory before KNN (distance-based)
- **Class Imbalance** — Downsampling majority class on IPL deliveries dataset
- **Confusion Matrix** — TP, TN, FP, FN; Precision, Recall, F1-Score
- **Elbow Method** — Inertia vs K to find optimal clusters
- **Sklearn Pipeline** — `Scaler → SelectFromModel → RandomForest` in one reusable object

---

## 📁 Datasets

| Dataset | Domain | Rows | Source |
|---|---|---|---|
| diamonds.csv | Retail | 53,940 | Kaggle |
| deliveries_1.csv | Sports/IPL | 1,50,454 | Kaggle |
| insurance.csv | Healthcare | 1,338 | Kaggle |
| titanic.csv | Historical | 891 | Kaggle |
| Mall_Customers.csv | Retail | 200 | Kaggle |
| winequality.csv | Food/Chemistry | 6,497 | UCI ML Repository |
| Student_Performance.csv | Education | 10,000 | Kaggle |
| auto-mpg.csv | Automotive | 398 | UCI ML Repository |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/sparks-to-ideas-aiml-internship.git
cd sparks-to-ideas-aiml-internship

# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

# Launch Jupyter
jupyter notebook
```

---

## 📜 Certificate

Successfully completed the **30-day onsite AI/ML Internship** at Sparks To Ideas, Ahmedabad.
Certificate issued by **Ms. Mansi Mishra**, HR Manager, Sparks To Ideas.

---

## 👤 Author

**Dhyan Shah**
B.Tech Computer Science Engineering | GCET, Vallabh Vidhyanagar | CVM University

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/YOUR_LINKEDIN)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/YOUR_USERNAME)

---

> *"The best way to learn ML is to build — not just read."*