# Heart Disease Prediction


### Model explored : Random Forests

This project was created with Random Forests machine learning algorithm in mind and involves the use of Bagging and hyperparameter tuning method, GridSearchCV alongside K-Folds to obtain the best results.

Pipelining was also used to automate feature extraction and implemented indivisually for categorical and numerical values to process the data with ease.

A plot was made to get the most important features in the tree.

The model was able to predict heart failure in a person from 13 features with a accuracy of nearly 83.5 % and a Recall score of 86%

The features available with us included :

1. Age : displays the age of the individual.
2. Sex : displays the gender of the individual using the following format : 1 = male 0 = female.
3. Chest-pain type : displays the type of chest-pain experienced by the individual using the following format : 1 = typical angina 2 = atypical angina 3 = non - anginal pain 4 = asymptotic
4. Resting Blood Pressure : displays the resting blood pressure value of an individual in mmHg (unit)
5. Serum Cholestrol : displays the serum cholestrol in mg/dl (unit)
6. Fasting Blood Sugar : compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false)
7. Resting ECG : 0 = normal 1 = having ST-T wave abnormality 2 = left ventricular hyperthrophy
8. Max heart rate achieved : displays the max heart rate achieved by an individual.
9. Exercise induced angina : 1 = yes 0 = no
10. ST depression induced by exercise relative to rest : displays the value which is integer or float.
11. Peak exercise ST segment : 1 = upsloping 2 = flat 3 = downsloping
12. Number of major vessels (0-3) colored by flourosopy : displays the value as integer or float.
13. Thal : displays the thalassemia : 3 = normal 6 = fixed defect 7 = reversable defect
14. Diagnosis of heart disease : Displays whether the individual is suffering from heart disease or not : 0 = absence 1,2,3,4 = present.
