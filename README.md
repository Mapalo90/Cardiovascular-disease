# Cardiovascular-disease
Cardiovascular diseases are the leading cause of death globally. It is therefore necessary to identify the causes and develop a system to predict heart attacks in an effective manner.

A health related dataset with variables such as age, sex, chest pain type (cpl), resting blood pressure (trestbps), serum cholesterol (chol), fasting blood sugar (fbs), resting electromagnetic results (restecg), maximum heart rate achieved (thalach), exercise induced angina (exang), ST depression induced by exercise relative to rest (old peak), slope of the peak exercise ST segment (slope), number of major vessels (0-3) colored by fluoroscopy (ca), thalassemia (thal), and target (distribution of the disease).

Data analysis was performed and it indicated that 
Heart attack cases are more prevalent in people with old age. Heart attacks are lower for people below the age of 55 and higher for people with age higher than 55.
Considering chest pain, people without a disease appear to have much fewer cases in variations 1, 2, and 3. People with a disease have a value of 0.
In cases where exercise induced angina is positive, there are more positive cases of the disease than those without the disease. In cases where exercise induced angina is negative, 70 % of the data has no heart attack cases.
The fbs is in almost the same proportions in patients with heart disease and those without the disease.
Results from the analysed data also showed that:
Patients' resting blood pressure appears to be the same among patients with and without the disease. However, the higher the bps, the more frequent the cases with heart attacks.
The higher the cholesterol levels, the more frequent the positive cases for the disease.
It can also be seen that the lower the heart rates, the more prevalent the heart disease cases.
As the oldpeak increases, patients with heart disease increase.
 
Feature selection was performed to find the features with the strongest influence on heart attack cases and the following were the features that were found to play a significant role in predicting the likelihood of heart cases: sex, exang, slope, ca, and thal which are all categorical data.

Data training was performed and it was found that the RandomForestClassier had a prediction score of 94.11 % higher than the logistics score of 84.85 %. However, the standard deviation in the RandomForestClassier model was 7.68 higher than that of the LogisticRegression model with 4.59. Hence, the uncertainty in the prediction of RandomForestClassier  is higher.
