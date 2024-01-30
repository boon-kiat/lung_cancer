## Prediction of Lung Cancer Severity using Machine Learning

### Module:
WQD7003 Data Analytics

### Group Members:
| Name | Matric ID|
| ---------------------- |:--------:|
| EE LIP KANG | S2025541 |
| HU LIANG LIANG | S2164046 |
| LEE YEN WEN | 17179615 |
| LOW BOON KIAT | 17138399 |
| Zhou Yao | S2177633 |

### Objective:
- To identify the attributes that could affect the severity of lung cancer.
- To predict the severity of lung cancer using a machine learning model. 

### Dataset:
- Lung cancer dataset on [Kaggle](https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link)
- Contain information on 1000 lung cancer patients. 
- Consist of 10 risk factors of lung cancer and 11 symptoms of lung cancer.

### CRISP-DM Methodology:
_Business Understanding:_  
- Our business is Alpha Healthcare, which provides healthcare services, such as diagnostic and health screening.
- Business goal is to identify individuals who are at high risk of lung cancer and provide targeted screening.
- Another business goal is to increase the takers of lung cancer screening by promoting screening tests to high-risk individuals, and grow revenue stemming from health screening.

_Data Understanding:_  
- Dataset contains information on 1000 lung cancer patients.
- Dataset contains 10 risk factors of lung cancer and 11 symptoms of lung cancer.

_Data Pre-processing:_  
- Handling missing values through imputation
- Handling outliers
- Binning to group similar values together

_Exploratory Data Analysis:_  
- Summary statistics
- Correlation heat map
- Univariate, multivariate analysis

_Modelling:_  
- Data partition
- Supervised machine learning i.e. Random Forest, Decision Tree, Logistic Regression, Gaussian Naive Bayes

_Result Evaluation & Interpretation:_  
- Consider accuracy, precision, recall and F1-score, the selected model is Logistic Regression.

_Model Deployment:_  
- Deploy the user input interface by creating sliders for each feature.
