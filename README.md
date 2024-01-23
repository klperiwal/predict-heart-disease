# Prediction of Heart Disease:

<b>Research Paper Link:  [Click Here](https://www.hindawi.com/journals/bmri/2023/6864343)</b>

<br>
<p align="center">
    <img src="https://prakashhospitals.in/wp-content/uploads/2022/04/HFDF56QNUNDHPJT6A5JH5RQYAE.webp" alt="Human Heart" width="35%" style="border-radius: 50%; box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);">
</p>
<h3 style="font-family: Times New Roman">PROBLEM STATEMENT:</h3>
In the age of abundant medical data and the growing field of Data Science, individuals are taking on the challenge of developing predictive indicators for diseases. Leading this mission is the battle against cardiovascular diseases (CVDs), which is the leading global cause of death, claims about 17.9 million lives annually, equivalent to 31% of all global fatalities. Among the many consequences of CVDs, <b>Heart Failure</b> is a significant concern.<br>

Individuals facing Heart Failure or those at a higher risk due to factors like hypertension, diabetes, hyperlipidemia, or existing health conditions, need timely detection and proactive management. This is where machine learning becomes a valuable ally, aiding in early intervention and effective disease management. By using advanced AI techniques, the goal is not just to automate the identification of cardiovascular issues but also to pave the way for a future where medical challenges can be systematically addressed and overcome with cutting-edge technology. As we navigate the complexities of heart health, the main focus remains on solving current problems and smoothly transitioning to the next frontier in healthcare innovation.
<br><br>

<H3 style="font-family: Times New Roman">AIM:</H3>

- Early Detection of Heart Disease using Machine Learning Model.
- Providing healthcare professionals with valuable insights, aiding in effective decision-making.
- Developing a model that is not only accurate but also accessible and efficient in a healthcare setting.
- Prepare for advancements in the field by keeping the model adaptable and capable of benefiting from future improvements.
<br>
<!--
<h3 style="font-family: Times New Roman" >DATASET ATTRIBUTES:</h3>    
- <b>Age</b>: Age of the patient[in years]
<br>- <b>Sex</b>: Gender of the patient[M:Male, F:Female]
<br>- <b>Chess Pain Type</b>: Chest pain type [TA:Typical Angina, ATA:Atypical Angina, NAP:Non-Anginal Pain, ASY:Asymptomatic]
<br>- <b>Resting BP</b>: Resting Blood Pressure [mm Hg]
<br>- <b>Cholestrol</b>: Serum Cholesterol level [mm/dl]
<br>- <b>Fasting BS</b>: Fasting Blood Sugar level [1: if FastingBS > 120 mg/dl, 0: otherwise]
<br>- <b>Resting ECG</b>: Resting ElectroCardiogram Results [Normal:Normal, ST:having ST-T wave abnormality, LVH:showing probable or definite left ventricular hypertrophy by Estes' criteria]
<br>- <b>Max HR</b>: Maximum HeartRate achieved [Numeric value between 60 and 202]
<br>- <b>Exercise Angina</b>: Exercise-induced angina [Y:Yes, N:No]
<br>- <b>OldPeak</b>: Oldpeak= ST[Numeric value measured in depression]
<br>- <b>ST_Slope</b>: Slope of the peak exercise ST segment [Up:upsloping, Flat:flat, Down:downsloping]
<br>- <b>HeartDisease</b>: Output Class [1:heart disease, 0:Normal]
<br><br>
-->

<b><h3 style="font-family: Times New Roman"> RESULT TABLE OF ALGORITHMS:</h3></b> 

|Sl No|ML Algorithm|Accuracy|Cross Validation Score|ROC-AUC Score|
|-|-|-|-|-|
|1|Logistic Regression|87.50%|91.12%|87.43%|
|2|Support Vector Classifier|87.50%|90.53%|87.43%|
|3|Decision Tree Classifier|84.78%|89.09%|84.62%|
|4|Random Forest Classifier|84.28%|92.91%|84.06%|
|5|K-Nearest Neighbors Classfier|81.52%|89.34%|81.36%|

<br>

<h3 style="font-family: Times New Roman" >CONCLUSION:</h3> 

- This dataset handles binary classification problems with the combination of both numerical and categorical features.
- SMEs (doctors or nurses) can be assisted by providing insights that enable them to take the next line of action.
- For feature engineering, data scaling was executed before the feature selection test. We might feel like we are tampering with the data before passing it to the tests but the results are the same irrespective of the order of the process.
- For modeling, hyperparameter tuning is not done. It can push the performances of the algorithms.
