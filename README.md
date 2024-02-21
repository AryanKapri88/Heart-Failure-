## Heart Failure Prediction 
![Heart](https://ars.els-cdn.com/content/image/1-s2.0-S0010482521004662-gr1.jpg)
                                                                          
### Overview

This project focuses on predicting heart failure using a dataset containing relevant clinical features using traditional feature engineering and ML approach. The dataset, named `heart_failure.csv`, has been analyzed using various machine learning models to assess their performance in predicting the likelihood of heart failure. The models used include Logistic Regression, Support Vector Classifier, Random Forest Classifier, Decision Tree Classifier, Gradient Boosting Classifier, Extreme-Gradient Boosting Classifier, and K Nearest Neighbors.

### Dataset

The dataset includes information on clinical indicators and patient characteristics related to heart failure. Key features such as age, sex, blood pressure, and various biomarkers are included.

### Models Used and It's accuracy

|ML Models|Train Accuracy|Test Accuracy|
|---|---|---|
|Logistic Regression|87.5%|83.6%|
|Support Vector Classifier|90.4%|85.8%|
|Random Forest Classifier|100.0%|83.6%|
|Decision Tree Classifier| 100.0%|76.08%|
|Gradient Boosting Classifier|93.5%|80.4%|
|Extreme- Gradient Boosting Classifier|100.0%|81.5%|
|K Nearest Neighbor (KNN)|100.0%|81.5%|

### Files Included

`main_code.ipynb`: Jupyter Notebook containing the code for data exploration, model training, and evaluation.

`heart_failure.csv`: Heart Failure Prediction dataset.

`requirements.txt`: List of required Python packages.

### Acknowledgment
-The Heart failure prediction dataset used in this project is sourced from [heartfailure.csv](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).




