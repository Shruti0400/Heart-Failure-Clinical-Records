# HeartFailure Clinical Records

#### Overview
This project explores clinical data from heart failure patients to identify key factors influencing patient survival. Through comprehensive exploratory data analysis (EDA) and predictive modeling, we aim to extract actionable health insights that support early diagnosis, personalized treatment, and improved patient outcomes.

By leveraging machine learning and statistical techniques, the project highlights critical indicators of mortality risk and builds models capable of predicting the likelihood of death in heart failure cases.

#### Dataset Overview
- File: heart_failure_clinical_records_dataset.csv

- Total Records: 299 patients

- Attributes: 13 clinical features + 1 target label

###### Clinical Features:
- age: Age of the patient (years)

- anaemia: Presence of anemia (1 = Yes, 0 = No)

- high_blood_pressure: Hypertension status (1 = Yes, 0 = No)

- creatinine_phosphokinase: Level of CPK enzyme in blood (mcg/L)

- diabetes: Diabetes status (1 = Yes, 0 = No)

- ejection_fraction: Percentage of blood ejected per heartbeat

- platelets: Platelet count (kiloplatelets/mL)

- serum_creatinine: Level of creatinine in the blood (mg/dL)

- serum_sodium: Sodium level (mEq/L)

- sex: Gender (1 = Male, 0 = Female)

- smoking: Smoking status (1 = Smoker, 0 = Non-smoker)

- time: Follow-up period in days

###### Target Variable:
- DEATH_EVENT: Indicates if the patient died during follow-up (1 = Yes, 0 = No)

#### Objectives
- Conduct exploratory data analysis to understand feature distributions and correlations

- Identify clinical parameters most strongly associated with heart failure mortality

- Build and compare classification models to predict patient outcomes

- Evaluate models using industry-standard performance metrics

#### Key Insights
- Patients with low ejection fraction and elevated serum creatinine levels showed a higher risk of mortality.

- Older age, anaemia, diabetes, and high blood pressure are correlated with increased risk of death.

- Significant statistical relationships were observed between several features and the DEATH_EVENT label, supporting their clinical relevance.

- Visual analysis revealed potential threshold values in biomarkers for targeted monitoring.

#### Tools & Technologies
- Python – Core language for data analysis and modeling

- Pandas, NumPy – Data wrangling and numerical operations

- Matplotlib, Seaborn – Exploratory and visual analytics

- Scikit-learn – Machine learning modeling and evaluation

- Jupyter Notebook – Development environment for interactive analysis

#### Model Evaluation
###### Models Implemented:
- Logistic Regression

- Random Forest Classifier

- Support Vector Machine (SVM)

- K-Nearest Neighbors (KNN)

###### Evaluation Metrics:
- Accuracy – Overall correctness of predictions

- Precision / Recall / F1 Score – Performance on positive class

- ROC-AUC – Ability to distinguish between classes

#### Conclusion
This project showcases how clinical data combined with predictive analytics can support better prognosis and treatment strategies for heart failure patients. The insights derived from the data highlight the most influential health indicators and demonstrate the potential of machine learning in healthcare risk prediction.

Future improvements could involve:

- Feature engineering (e.g., BMI, comorbidity scores)

- Hyperparameter tuning

- Deployment as a diagnostic decision support tool

