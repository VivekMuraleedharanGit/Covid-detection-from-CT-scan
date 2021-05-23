# Covid-detection-from-CT-scan

Corona - COVID19 virus affects the respiratory system of healthy individual & Chest X -Ray is one of the important imaging methods to identify the corona virus.

With the Chest X - Ray dataset, Develop a Machine Learning Model to classify the X Rays of Healthy vs Pneumonia (Corona) affected patients & this model powers the AI application to test the Corona Virus in Faster Phase.


## Content
Collection Chest X Ray of Healthy vs Pneumonia (Corona) affected patients infected patients along with few other categories such as SARS (Severe Acute Respiratory Syndrome ) ,Streptococcus & ARDS (Acute Respiratory Distress Syndrome)

Images name and labels are available in ChestXrayCorona_Metadata.csv

COVID 19 - https://en.wikipedia.org/wiki/Coronavirus_disease_2019
ARDS - https://en.wikipedia.org/wiki/Acute_respiratory_distress_syndrome
Streptococcus - https://en.wikipedia.org/wiki/Streptococcus
SARS - https://en.wikipedia.org/wiki/Severe_acute_respiratory_syndrome

Original Source :- https://github.com/ieee8023/covid-chestxray-dataset

## Model
Trained on Inception V3 from Keras 
### Classification report
   precision    recall  f1-score   support

           0       0.44      0.94      0.60       234
           1       0.89      0.26      0.41       390

    accuracy                           0.52       624
   macro avg       0.66      0.60      0.50       624
weighted avg       0.72      0.52      0.48       624
