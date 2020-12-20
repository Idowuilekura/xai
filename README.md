# xai
Heart disease describes a range of conditions that affect your heart. With growing stress, the number of cases of heart diseases are increasing rapidly.

According to the World Health Organisation(WHO), Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year. 17.9 million people die each year from CVDs, an estimated 31% of all deaths worldwide.

Problem Statement The doctors of Health Hospital in Zastra wish to incorporate Data Science into their workings. Seeing the rising cases of heart diseases, they are specially interested in predicting the presence of heart disease in a person using some existing data. The first step they are taking towards it is to conduct a Datathon to find the best Machine Learning Engineers available out there.

# Objective 
The idea behind this ML project is to build an ML model to determine if heart disease is present or not i.e if the target is 1 or 0.

# Context
The doctors of Health Hospital in Zastra are tired of looking at new proposals for detecting heart disease using a Machine Learning model. They wish to understand the model and not rely on a magical black box. Can you help them out by first creating a model and then explaining how these models work?

# Data Description

- age: Age in years
- sex: 1 = male, 0 = female
- cp: Chest pain type
- trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
- chol: serum cholesterol in mg/dl
- fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: The slope of the peak exercise ST segment
- ca: Number of major vessels (0-4) colored by fluoroscopy
- thal: 0 = null, 1 = fixed defect found, 2 = blood flow is normal, 3 = reversible defect found
- target: 1 = Heart disease present, 0 = Heart disease not present

Evaluation Criteria Submissions are evaluated using F1 Score

This is my assignment on explainable AI as part of Dphi's Advanced machine learning bootcamp. 
idowu_ilekura_XAI.ipynb contains detailed analysis of the model with the aid of SHAP, heart_disease_prediction.ipynb contains codes used for Dphi's datathon(similar to kaggle competitions and Zindi competitions)
