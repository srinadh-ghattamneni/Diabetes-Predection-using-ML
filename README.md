# 🩺 Diabetes Prediction using Machine Learning

## 📌 Introduction
This project aims to develop a robust machine learning pipeline to predict diabetes status accurately using medical and laboratory data collected from hospitals in Iraq. With the growing concern over diabetes worldwide, early detection using data-driven approaches can significantly improve patient outcomes.

---
## 📊 Dataset Overview

SOURCE: https://data.mendeley.com/datasets/wj9rwkp9c2/1

The dataset includes information from **1,000 patients**, sourced from:
- **Medical City Hospital**
- **Al-Kindy Teaching Hospital**, Iraq

### 🔑 Key Features:
- Age: Age 
- Gender: Gender 
- Body Mass Index (BMI): Body Mass Index
- Urea: Urea (no abbreviation)
- Cr: Creatinine
- HbA1c: Hemoglobin A1c
- Chol: Cholesterol
- TG: Triglycerides
- HDL: High-Density Lipoprotein
- LDL: Low-Density Lipoprotein
- VLDL: Very Low-Density Lipoprotein

- Diabetes status:  
  - `Non-Diabetic`,  
  - `Predicted-Diabetic`,  
  - `Diabetic`

---

## ⚙️ Methodology

### 🔄 Data Preprocessing
- Removal of irrelevant or noisy features
- Categorical encoding using `LabelEncoder`
- Missing value inspection and cleanup
- Feature normalization using `StandardScaler`
- Handling class imbalance using:
  - `SMOTENC` (SMOTE for mixed categorical/numeric data)

### 🧠 Model Building
Four classification algorithms were implemented:
- 🌲 Random Forest
- 🌿 Decision Tree *(Optional - if added later)*
- 📍 K-Nearest Neighbors (KNN)
- 🌀 Support Vector Machine (SVM)

Each model was integrated with a pipeline:
- Scaling → Resampling → Classification
- Hyperparameter tuning using `GridSearchCV` with 5-fold cross-validation
- Class balancing using `class_weight='balanced'` and SMOTENC

### 📈 Evaluation Metrics
- Accuracy
- F1-score (Macro-averaged)
- ROC AUC Score (Macro-averaged)
- Confusion Matrix
- ROC Curve
- Learning Curve (Training vs Validation scores)

---

## ✅ Results

| Model                  | Accuracy | F1-Score (Macro) | 
|------------------------|----------|------------------|
| Random Forest          | 98.5     | 95.5             | 
| Logistic Regression    | 92.5     | 76.8             |  
| K-Nearest Neighbors    | 95.5     | 85.9             |  
| Support Vector Machine | 95.5     | 84.3             |  

📝 Detailed evaluation reports and ROC curves are available in the Jupyter notebook.

---

## 🚀 How to Use

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/yourusername/diabetes-prediction-ml.git
cd diabetes-prediction-ml



### Prerequisites
You can install all dependencies via pip:
pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn



## License
- This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
-For any inquiries, please reach out to srinadhghattamneni1990@gmail.com.

## Fork and Contribute
- If you find this project interesting or useful, please fork the repository and star it. Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or bug fixes.  
