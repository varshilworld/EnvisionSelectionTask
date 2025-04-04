# Credit Card Fraud Detection

This project applies two machine learning models — **Logistic Regression** and **Random Forest Classifier** — to detect fraudulent transactions using a balanced dataset.

## 📂 Dataset

- File: `dataset.csv`
- The dataset is assumed to be **clean** and **balanced**.
- Target variable: `Class`  
  - `0`: Non-fraudulent  
  - `1`: Fraudulent

## 🔄 Workflow

1. **Load Data** with `pandas`
2. **Clean Data** by removing missing values
3. **Split Data** into features (`X`) and target (`y`)
4. **Train-Test Split** (80% train, 20% test)
5. **Scale Features** using `StandardScaler` (for logistic regression)
6. **Train Models**:  
   - Logistic Regression  
   - Random Forest Classifier
7. **Evaluate Accuracy** of both models on the test set

## 🔍 Evaluation

Models are compared using accuracy score. Additional metrics like precision, recall, and confusion matrix can be added for deeper insights.

## 📦 Requirements

Install dependencies using:

```bash
pip install pandas scikit-learn
