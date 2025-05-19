# heart-disease-prediction

This repository contains a simple machine learning project that predicts whether a person has heart disease or not using **Logistic Regression**. It is a **binary classification** problem.

---

## 📁 Dataset

- **File**: `Heart.csv`
- **Shape**: (918, 12)
- Each row represents a patient with various health-related features.

---

## 🧰 Libraries & Tools Used

- **Python**
- **Libraries**:
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `sklearn`
    - `LogisticRegression`
    - `LabelEncoder`
    - `train_test_split`
    - `confusion_matrix`
    - `accuracy_score`
    - `roc_curve`, `auc`

---

## 🔁 Workflow

1. **Data Preprocessing**
   - Encoded categorical values using `LabelEncoder`
   - Computed correlation matrix
   - Visualized using heatmap (`seaborn`)
   - Dropped unnecessary or less important columns

2. **Model Building**
   - Splitting data using `train_test_split`
   - Trained using `LogisticRegression`

3. **Model Evaluation**
   - Made predictions on test data
   - Evaluated using:
     - Confusion Matrix
     - Accuracy Score
     - ROC Curve
     - AUC Score

---

## 📈 Results

- Visual insights from correlation matrix and heatmap
- Confusion matrix to validate predictions
- ROC-AUC curve demonstrates classification performance

---


### 1. Clone the Repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
