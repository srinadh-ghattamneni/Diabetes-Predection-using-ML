# Diabetes Prediction using Machine Learning

## Introduction
This project focuses on developing a robust machine learning model to accurately predict diabetes using a diverse dataset collected from medical centers in Iraq. Given the global rise in diabetes cases, this project aims to aid in early diagnosis and effective management of the disease.

## Dataset
The dataset, sourced from Medical City Hospital and Al-Kindy Teaching Hospital, includes medical and laboratory information from 1000 patients. Key features include blood sugar levels, age, gender, BMI, cholesterol levels, and the diabetes status of patients (Diabetic, Non-Diabetic, or Predicted-Diabetic).

## Methodology
### Data Preprocessing:
- Encoding categorical variables.
- Addressing class imbalance using SMOTE and Random Under-sampling.
- Normalizing features using StandardScaler and MinMaxScaler.

### Model Building:
- Classification algorithms used: Random Forest, Decision Tree, K-Nearest Neighbors (KNN), and Support Vector Machine (SVC).
- Hyperparameter tuning conducted with GridSearchCV.

### Evaluation:
- Models assessed on accuracy, precision, recall, and F1-score.
- Confusion matrices used for detailed insights.

## Results
The Random Forest classifier demonstrated the best performance with an accuracy of 98.6%.

## Conclusion
This project underscores the potential of machine learning in aiding early diagnosis and treatment of diabetes, offering valuable insights into the effectiveness of different algorithms.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-ml.git
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn



## License
- This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
-For any inquiries, please reach out to srinadhghattamneni1990@gmail.com.

## Fork and Contribute
- If you find this project interesting or useful, please fork the repository and star it. Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or bug fixes.   rewrite code for md file
