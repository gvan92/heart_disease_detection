# heart_disease_detection
Using machine learning to predict heart disease (Python)

The dataset used is the Cleveland Heart Disease database from the UCI Repository and can be viewed and downloaded here: https://archive.ics.uci.edu/ml/datasets/Heart+Disease. This dataset uses a subset of 14 out of originally 76 attributes that is part of a much larger dataset. Of the 14 attributes, 13 will be used as characteristic predictors for classifying whether or not there is presence of heart disease. The other attribute is the labels for the dataset which consist of 5 integer classes from 0 to 4 where 0 is no presence of heart disease and 1 through 4 is varying presences of heart disease. In this project we will only classify whether or not there is any presence of heart disease, hence we grouped the labels 1 through 4 into one single value of “1” so that the label is will be binary, which is described more in the “Map Data” section.

The 14 attributes that will be used in this dataset are:

    Age: in years
    Sex: 1 = male; 0 = female
    Chest Pain (cp): type a. Value 1: typical angina b. Value 2: atypical angina c. Value 3: non-anginal pain d. Value 4: asymptomatic
    Resting Blood Pressure (trestbps): in mm Hg on admission to the hospital
    Serum Cholestoral (chol): in mg/dl
    Fasting Blood Sugar > 120 mg/dl (fbs): 1 = true; 0 = false
    Resting Electrocardiographic (restecg): results a. Value 0: normal b. Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) c. Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
    Maximum Heart Rate Achieved (thalach): value
    Exercise Induced Angina (exang): 1 = yes; 0 = no
    ST Depression (oldpeak): induced by exercise relative to rest
    Slope of the Peak Exercise ST Segment (slope): 1, 2, or 3
    Number of Major Vessels (ca): 0-3 colored by flourosopy
    Thalassemia (thal): 3 = normal; 6 = fixed defect; 7 = reversable defect
    Diagnosis of Heart Disease (num): angiographic disease status 0-4; ground truth labels

I used Support Vector Machine, Decision Tree, Neural Network and K-nearest neighbor models in this project and compared the results.
