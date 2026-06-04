# CodeAlpha Tasks — Machine Learning Projects

## 📁 Task 4 — Disease Prediction from Medical Data

### Breast Cancer Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![sklearn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-98.25%25-brightgreen)

### 📌 Objective
Predict whether a breast tumor is **Malignant** or **Benign** 
based on 30 medical measurements.

### 📊 Dataset
- Source: UCI ML Repository (via sklearn)
- Samples: 569 patients
- Features: 30 medical measurements
- Classes: Malignant (212) | Benign (357)

### 🤖 Models Used
| Model | Accuracy |
|---|---|
| Logistic Regression | 97.37% |
| SVM | **98.25% 🏆** |
| Random Forest | 96.49% |

### 🏆 Best Model — SVM
- Accuracy: 98.25%
- Missed Cancer Cases: 0 ⭐
- Malignant Precision: 100%

### 🔝 Top Features
1. worst area
2. worst concave points
3. mean concave points

### 🛠️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook Breast_Cancer_Project.ipynb
```
