<h1>Data Mining - Predicting patients at risk of diabetes </h1>


<h2>Description</h2>
Predicting diabetic patient from non-diabetic patient using gradient boosted models(xgboost, catboost, so forth), multi-layer perceptron with TensorFlow and SK-learn libraries. The Diabetes Health Indicators Dataset contains healthcare statistics and lifestyle survey information about people in general along with their diagnosis of diabetes. The 35 features consist of some demographics, lab test results, and answers to survey questions for each patient. The target variable for classification is whether a patient has diabetes or is pre-diabetic (1), or healthy (0).
<br />
<h2>Data Source</h2>
### [Source](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators)


<h2>Languages </h2>

- <b>Python</b> 


<h2>Environments Used </h2>

- <b>Google Collab</b>

<h2>Results </h2>

<p align="center">
Correlation Matrix : <br/>
<img src="https://i.imgur.com/ddET1jU.png" height="60%" width="60%" alt="Correlation Matrix"/>
<br />
<br />

<p align="center">
Roc-AUC of esemble models: <br/>
<img src="https://i.imgur.com/BYUxIN0.png" height="60%" width="60%" alt="Esemble models"/>
<br />
<br />
 
<p align="center">
Results Matrix all Models(esembels and Multi-Layer Perceptron (MLP): <br/>
<img src="https://i.imgur.com/n9fwCAp.png" height="60%" width="60%" alt="All models"/>
<br />
<br />

- <b>It makes sense for the sensitivity to be low and log loss high since no feature had a correlation value of 3 or above with outcome variable. The data set has poor features and better feature sets are needed if we want better results in capturing diabetic and pre-diabetic patients</b>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
