# Prediction of Heart Disease:

<center>
    <img src="https://prakashhospitals.in/wp-content/uploads/2022/04/HFDF56QNUNDHPJT6A5JH5RQYAE.webp" alt="Human Heart" width="35%">
</center>

<h3 style="font-family: Times New Roman">Problem Statement:</h3>
In the era of abundant medical data and the burgeoning field of Data Science, numerous startups are stepping up to confront the challenge of developing predictive indicators for impending diseases. At the forefront of this mission is the battle against cardiovascular diseases (CVDs), which stand as the leading global cause of death, claiming approximately 17.9 million lives annually equivalent to 31% of all global fatalities. Among the myriad consequences of CVDs, heart failure looms large.<br>

Individuals grappling with cardiovascular diseases or those at elevated cardiovascular risk—attributable to factors such as hypertension, diabetes, hyperlipidemia, or existing health conditions require timely detection and proactive management. Enter the realm of machine learning, a powerful ally in the quest for early intervention and effective disease management. By leveraging advanced AI techniques, we aim not only to automate the identification of cardiovascular issues but also to pave the way for a future where medical challenges can be systematically addressed and overcome with the aid of cutting-edge technology. As we tackle the complexities of heart health, our sights remain set on solving current problems and seamlessly transitioning to the next frontier in healthcare innovation.
<br><br>

<H3 style="font-family: Times New Roman">Aim:</H3>
- To classify / predict whether a patient is prone to heart failure depending on multiple attributes.<br>
- It is a <b>Binary Classification</b> with multiple numerical and categorical features.
<br><br>


<h3 style="font-family: Times New Roman" >Dataset Attributes:</h3>    
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

<br>
<br>

## <div style="font-family: Times New Roman; padding: 12px; line-height: 1;">Algorithm Result Table</div>

|Sr. No.|ML Algorithm|Accuracy|Cross Validation Score|ROC AUC Score|
|-|-|-|-|-|
|1|Logistic Regression|87.50%|91.12%|87.43%|
|2|Support Vector Classifier|87.50%|90.53%|87.43%|
|3|Decision Tree Classifier|84.78%|89.09%|84.62%|
|4|Random Forest Classifier|84.24%|92.91%|84.06%|
|5|K-Nearest Neighbors Classfier|81.52%|89.34%|81.36%|

<br>

# <div style="font-family: Times New Roman; padding: 12px; line-height: 1;">Conclusion</div>

- This dataset is great for understanding how to handle binary classification problems with the combination of numerical and categorical features.

- SMEs (doctors or nurses) can be assisted by providing insights that enables them to take the next line of action.

- For feature engineering, it might feel confusing about the order of the processes. In this case, data scaling was executed before the feature selection test. We might feel like we are tampering the data before passing it to the tests but the results are same irrespective of the order of the process. (Try it out!)

- For modeling, hyperparameter tuning is not done. It can push the performances of the algorithms. Overall the algorithm performances are good.
