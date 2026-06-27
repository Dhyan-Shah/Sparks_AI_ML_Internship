# Machine Learning Practice Set – 30 Hands-on Problems 🚀

This repository contains solutions to **30 Machine Learning practice problems** covering **Regression, Classification, Clustering, Model Evaluation, Hyperparameter Tuning, Feature Selection, and Pipelines** using Python and Scikit-learn.

The purpose of this practice set was to gain practical understanding of implementing different Machine Learning algorithms on real-world datasets.

---

## 📚 Topics Covered

The 30 questions are divided into major Machine Learning categories.

---

# 1️⃣ Regression Problems

Implemented regression algorithms for predicting continuous values.

Algorithms used:

* Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Decision Tree Regressor
* Random Forest Regressor
* KNN Regressor

Problems solved:

* Predict company profit from startup expenses
* Predict sales revenue from TV advertising budget
* Predict car selling price
* Predict insurance medical charges
* Predict student academic performance index
* Predict employee salary range using Decision Tree Regressor
* Predict car selling price using Random Forest Regressor
* Predict insurance charges using Random Forest with Cross Validation

Concepts practiced:

* R² Score
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

# 2️⃣ Classification Problems

Implemented classification algorithms for predicting categories/classes.

Algorithms used:

* Logistic Regression
* K-Nearest Neighbors (KNN Classifier)
* Decision Tree Classifier
* Random Forest Classifier

Problems solved:

* Predict product purchase behavior
* Employee attrition prediction
* Titanic survival prediction
* Loan approval prediction
* Credit card fraud detection
* Student pass/fail prediction
* Wine quality classification
* Customer insurance category prediction
* Diamond price tier prediction
* Employee attrition using Random Forest

Concepts practiced:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

# 3️⃣ Clustering Problems

Implemented unsupervised learning techniques to discover hidden patterns.

Algorithms used:

* K-Means Clustering
* DBSCAN

Problems solved:

* Mall customer segmentation
* Customer segmentation based on full profile
* Air pollution risk zone clustering
* Outlier detection using DBSCAN
* Customer segmentation using DBSCAN with Silhouette Score evaluation

Concepts practiced:

* Elbow Method
* Inertia
* Cluster Centroids
* Silhouette Score
* Outlier Detection

---

# 4️⃣ Decision Tree Models

Worked with both classification and regression trees.

Implemented:

* Titanic survival prediction using Decision Tree
* Insurance category prediction using Decision Tree
* Diamond price classification using Decision Tree
* Wine quality category prediction using Decision Tree
* Employee salary prediction using Decision Tree Regressor

Concepts practiced:

* Gini Index
* Entropy
* Information Gain
* Tree Visualization
* Feature Importance

Gini formula:

```text id="pd87k3"
Gini = 1 - Σ(pi²)
```

Entropy formula:

```text id="v8sl20"
Entropy = -Σ(pi log₂ pi)
```

---

# 5️⃣ Random Forest Models

Implemented ensemble learning models.

Implemented:

* Titanic survival prediction using Random Forest
* Employee attrition prediction using Random Forest
* Car selling price prediction using Random Forest Regressor
* Insurance charge prediction using Random Forest Regressor
* Wine quality prediction using full pipeline + Random Forest

Concepts practiced:

* Ensemble Learning
* Bagging
* Multiple Decision Trees
* Feature Importance

---

# 6️⃣ Hyperparameter Tuning

Optimized models using:

* GridSearchCV
* RandomizedSearchCV
* Cross Validation

Applied on:

* KNN
* Decision Tree
* Random Forest
* DBSCAN parameter tuning

Concepts practiced:

* Parameter Optimization
* Model Selection
* Cross Validation

---

# 7️⃣ Feature Engineering & Preprocessing

Performed preprocessing tasks including:

* Handling Missing Values
* Label Encoding
* One Hot Encoding
* Feature Scaling
* Feature Selection

Libraries used:

* StandardScaler
* LabelEncoder
* OneHotEncoder
* SelectKBest

Standardization:

```text id="gt9wq1"
z = (x - μ) / σ
```

---

# 8️⃣ Machine Learning Pipeline

Built complete ML pipeline combining:

* Data Preprocessing
* Feature Selection
* Model Training

Pipeline:

```text id="j6h29d"
StandardScaler
      ↓
SelectKBest
      ↓
RandomForestClassifier
      ↓
Prediction
```

Project:

* Wine Quality Prediction Pipeline

---

## 🛠 Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Skills Practiced

✔ Data Cleaning
✔ Exploratory Data Analysis
✔ Feature Engineering
✔ Model Training
✔ Model Evaluation
✔ Hyperparameter Tuning
✔ Cross Validation
✔ Clustering
✔ Pipeline Building
✔ Ensemble Learning

---

## Learning Outcome

After completing these 30 problems, I gained practical experience in:

* Supervised Learning
* Unsupervised Learning
* Regression Models
* Classification Models
* Clustering Algorithms
* Feature Selection
* Hyperparameter Optimization
* End-to-End Machine Learning Workflow

---

## Author

**Dhyan Shah**
B.Tech Computer Engineering
Learning AI/ML through hands-on implementation

GitHub: https://github.com/Dhyan-Shah/Sparks_AI_ML_Internship

---

⭐ This repository documents my journey of solving 30 Machine Learning practice problems and strengthening my ML fundamentals.
