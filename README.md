This project presents a comparative study of multiple machine learning algorithms to predict fetal health status using Cardiotocogram (CTG) data. The objective is to enhance early detection of fetal complications and support clinicians in making data-driven decisions. The classification task involves predicting fetal health as Normal, Suspect, or Pathological based on physiological features such as fetal heart rate, accelerations, movements, and uterine contractions.

We implemented and evaluated four algorithms: K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest (RF), and Gradient Boosting (GB). Among these, Gradient Boosting achieved the best performance with an accuracy of 96.92%.

 Dataset:

The dataset used for this study was sourced from Kaggle and contains 2,113 records. It includes a variety of physiological features such as baseline fetal heart rate (FHR), accelerations, fetal movements, uterine contractions, and others. These features provide critical indicators of fetal well-being and were used to train and evaluate the machine learning models.


Methodology:
The project followed a structured machine learning pipeline beginning with data cleaning and preprocessing to ensure the quality and consistency of the dataset. This was followed by exploratory data analysis (EDA) to uncover patterns, correlations, and distributions within the features. To enhance model performance, feature selection was performed using the SelectKBest method, identifying the most relevant attributes for classification. The selected features were then used to train multiple models, with hyperparameter tuning applied to optimize their performance. Finally, the models were evaluated using key performance metrics, including accuracy, precision, recall, and F1-score, to ensure a comprehensive comparison of their predictive capabilities.


Results:
Gradient Boosting outperformed all other models with the highest testing accuracy and minimal error margin. Proper handling of class imbalance and careful tuning of model parameters significantly contributed to improved performance.
