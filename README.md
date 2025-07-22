# 🧠 Fetal Health Prediction Using Machine Learning

This project aims to predict fetal health conditions using machine learning models applied to Cardiotocogram (CTG) data. By leveraging physiological signals, this model can assist healthcare professionals in early detection of fetal abnormalities, thus improving maternal and fetal outcomes.

---

## 📌 Objective

To classify fetal health into one of the following categories:
- **Normal**
- **Suspect**
- **Pathological**

This classification is based on several physiological parameters such as:
- Fetal Heart Rate (FHR)
- Accelerations
- Movements
- Uterine Contractions
- Variability indices

---

## 📊 Dataset

- **Source**: [Kaggle - Fetal Health Classification](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
- **Records**: 2,113
- **Features**: 21 numerical indicators related to fetal heart rate and uterine contraction patterns
- **Target**: `fetal_health` (0 = Normal, 1 = Suspect, 2 = Pathological)

---

## 🧪 Methodology

1. **Data Preprocessing**  
   - Checked for missing values  
   - Standardized features for uniform scaling  

2. **Exploratory Data Analysis (EDA)**  
   - Correlation heatmap  
   - Feature distributions  
   - Class imbalance analysis  

3. **Feature Selection**  
   - Used `SelectKBest` for extracting top-performing features  

4. **Model Building & Evaluation**  
   Trained the following models:
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Random Forest (RF)
   - Gradient Boosting (GB)

5. **Model Tuning**  
   - Applied hyperparameter optimization using GridSearchCV  
   - Evaluated using:
     - Accuracy
     - Precision
     - Recall
     - F1-Score

---

## 🏆 Results

| Model             | Accuracy (%) |
|------------------|---------------|
| KNN              | **92.67**     |
| SVM              | **95.50**     |
| Random Forest    | **96.69**     |
| Gradient Boosting | **96.92**    |

> **Gradient Boosting** performed the best overall with excellent precision and recall values across all classes.

---

## 🧰 Technologies Used

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` for ML algorithms and evaluation

---
