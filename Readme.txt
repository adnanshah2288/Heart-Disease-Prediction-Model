Heart Disease Prediction Model
This is a classification model designed to predict whether a person has heart disease based on various medical and health-related features. The model analyzes patient data and provides a binary classification:

1 → Heart Disease Present
0 → No Heart Disease

Disease:
Input Features (X) – Independent Variables
These are the 13 features used by the model for prediction:

Feature Name 	Description
age	        Age of the patient (in years)
sex	        Gender (0 = Female, 1 = Male)
cp	        Chest pain type (0–3)
trestbps	Resting blood pressure (mm Hg)
chol	        Serum cholesterol (mg/dL)
fbs	        Fasting blood sugar (1 = >120 mg/dL, 0 = normal)
restecg	        Resting ECG results (0–2)
thalach   	Maximum heart rate achieved
exang	    	Exercise-induced angina (1 = Yes, 0 = No)
oldpeak		ST depression induced by exercise
slope		Slope of the peak exercise ST segment (0–2)
ca		Number of major vessels colored by fluoroscopy (0–3)
thal		Thalassemia type (1–3)


Target Variable (Y) – Dependent Variable
Target Name	Description
target		The presence of heart disease (1 = Disease, 0 = No Disease)

Model Type:
Since the target variable is binary (0 or 1), this is a Classification Model.
✅ KNeighbors Classifier

