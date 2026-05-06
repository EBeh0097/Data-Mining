# Data Mining with XGBoost and TensorFlow

## Project Overview


<h2>Description</h2>
Predicting diabetic patient from non-diabetic patient using gradient boosted models(xgboost, catboost, so forth), multi-layer perceptron with TensorFlow and SK-learn libraries. The Diabetes Health Indicators Dataset contains healthcare statistics and lifestyle survey information about people in general along with their diagnosis of diabetes. The 35 features consist of some demographics, lab test results, and answers to survey questions for each patient. The target variable for classification is whether a patient has diabetes or is pre-diabetic (1), or healthy (0).
<br />
<h2>Data Source</h2>
### [Source](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators)

## Models Implemented

The notebook implemented and evaluated:

XGBoost Classifier
LightGBM Classifier
CatBoost Classifier
YDF Gradient Boosted Trees
TensorFlow / Deep Learning workflow concepts

### Results Statistics
1. XGBoost Results
Testing Performance
Accuracy: 86.34%
ROC-AUC: 82.37%
Training Performance
Accuracy: 87.65%
ROC-AUC: 85.69%
Sensitivity: 21.40%
Specificity: 98.38%
Key Insight

XGBoost produced the most balanced performance overall with:

Strong specificity
Stable ROC-AUC performance
Reliable predictive accuracy

The notebook concluded that this model was preferable because of its stronger balance between sensitivity and specificity.

2. Correlated Feature XGBoost Model
Testing Performance
Accuracy: 86.49%
ROC-AUC: 80.42%
Training Performance
Accuracy: 86.61%
ROC-AUC: 81.39%
Sensitivity: 13.11%
Specificity: 98.50%
Key Insight

Using only highly correlated features slightly improved raw accuracy but reduced:

ROC performance
Sensitivity
Overall model balance

3. LightGBM Results
Testing Performance
Accuracy: 86.55%
ROC-AUC: 82.69%
Sensitivity: 16.40%
Specificity: 97.91%
Training Performance
Accuracy: 86.99%
ROC-AUC: 84.13%
Key Insight

LightGBM demonstrated:

Very stable performance
Strong specificity
Competitive ROC-AUC scores
Good scalability potential

4. YDF Gradient Boosted Trees Results
Testing Performance
Accuracy: 86.56%
ROC-AUC: 82.73%
Sensitivity: 16.83%
Specificity: 97.85%
Training Performance
Accuracy: 87.03%
ROC-AUC: 84.02%
Key Insight

The YDF model performed similarly to LightGBM and showed:

Consistent predictive behavior
Strong classification reliability
Good enterprise AI applicability

5. CatBoost Results
Testing Performance
Accuracy: 86.47%
ROC-AUC: 82.54%
Sensitivity: 17.23%
Specificity: 97.68%
Training Performance
Accuracy: 88.03%
ROC-AUC: 85.84%
Key Insight

CatBoost achieved:

The highest training accuracy
Strong ROC-AUC performance
Excellent handling of structured data
Overall Findings

#### The project demonstrated that all Gradient Boosted models produced:

Strong predictive accuracy
Excellent specificity
Competitive ROC-AUC performance
Main Conclusions
Ensemble learning significantly improved predictive performance
XGBoost provided the best overall balance
Feature selection impacts sensitivity and ROC-AUC behavior
Gradient Boosting models are highly effective for structured predictive analytics workflows
Technical Skills Demonstrated

### This notebook demonstrates practical experience with:

XGBoost
LightGBM
CatBoost
Gradient Boosted Trees
TensorFlow concepts
ROC-AUC analysis
Feature engineering
Predictive analytics
Hyperparameter evaluation
Machine Learning model comparison
Enterprise AI experimentation workflows

### These are highly relevant skills for:

Health Data Scientist roles
AI Engineer positions
Machine Learning Engineer opportunities
Predictive Analytics and Healthcare AI roles
---



## Author

Emmanuel Ebeh  
Health Data Scientist | AI Engineer | Machine Learning Researcher
