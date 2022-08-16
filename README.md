# Cardiovascular-Risk-Prediction
Cardiovascular Risk Prediction
![CAD-1](https://user-images.githubusercontent.com/99146783/184786001-3c48aaa1-81b5-4377-b289-5b711ea83c83.png)

![chd-2](https://user-images.githubusercontent.com/99146783/184785343-6db3087f-d027-4c99-ba7c-ab240b24c9a1.png)

# Introduction:
### Coronary heart disease is a type of heart disease where the arteries of the heart cannot deliver enough oxygen-rich blood to the heart. Coronary artery disease affects the larger coronary arteries on the surface of the heart. Another type of heart disease, called coronary microvascular disease, affects the tiny arteries in the heart muscle. Coronary microvascular disease is more common in women. Symptoms of coronary heart disease may be different from person to person, even if they have the same type of coronary heart disease.
## Problem Statement:
Look at the given dataset and find the distribution of each feature. Look for null values and outliers and replace or remove them if it is meaningful for our study. The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patient's information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic and behavioral and medical risk factors. Use appropriate metrics to compare the performance of machine learning algorithms.
# conclusions:
* Age is ranging from 30 to 70.
* cigsperday is ranging from 0 to 70.
* total cholestral is ranging from 100 to 700.
* sysbp is ranging from 100 to 300.
* diabp is ranging from 40 to 140.
* BMI is ranging from 15 to 55.
* heart rate is ranging from 40 to 140.
* glucose level is from 40 to 400.
* Females are more than number of males in our dataset but number of males prone to heart disease are more compared to females.
* higher education people are less but all education level people having equal share of heart disease prone.
* we have imbalanced dataset. So we buit machine learning algorithms in two scenarios. They are
* without upsample (no resample)
* with upsample (resample)
## No Resampling on dataset:
### F1 Score on test dataset :
* Naive Bayes Classifier: 0.57
* Random Forest Classifier: 0.46
* XGBoost Classifier: 0.51

## Resampling dataset case:
### F1 score on test datsset :
* Logistic Regression: 0.66
* Naive Bayes Classifier: 0.51
* Decision Tree Classifier: 0.67
* KNN Classifier: 0.78
* XGBoost Classifier: 0.85
* Random Forest Classifier: 0.7
