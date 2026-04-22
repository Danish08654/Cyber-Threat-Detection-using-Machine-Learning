##  Overview
This project implements a **production-ready machine learning pipeline** to detect cyber threats using structured cybersecurity data.

It focuses on solving real-world challenges such as **data imbalance, feature engineering, and model reliability**.

---

##  Objective
- Classify network activity as **normal or malicious**
- Handle imbalanced cybersecurity data
- Build a complete end-to-end ML system

---

##  Pipeline

### 1. Data Preprocessing
- Handled missing values (numeric + categorical)
- Removed duplicates
- Dropped high-cardinality features (e.g., IP address)

### 2. Feature Engineering
- Extracted time-based features from timestamps
- Created behavioral indicators (e.g., night attacks, severity flags)

### 3. Encoding
- Label encoding for categorical variables
- Separate encoding for target variable

### 4. Train-Test Split
- Stratified split to preserve class distribution

### 5. Scaling
- StandardScaler applied to numerical features

### 6. Class Imbalance Handling
- Applied **SMOTE** to balance dataset

### 7. Model
- Random Forest Classifier

### 8. Evaluation
- Accuracy
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

### 9. Feature Importance
- Visualized key contributing features

---

##  Results
The model achieved strong performance while maintaining balanced predictions across classes.

---

##  Tech Stack
- Python
- Scikit-learn
- Pandas / NumPy
- Matplotlib
- Imbalanced-learn (SMOTE)

