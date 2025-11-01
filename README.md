# music_classification

## Introduction
The project is about prediction music genre based on some charachteristics of track.

## Definition of problem
The problem is to preprocess dataset by removing duplicates, anomalies and process missing values and predict music genre by 3 models: SVM, KNN, Random Forest.

## Data description
The data was taken from kaggle datasets. It has about 18000 records and 17 columns.
Columns have types as follows:
|#|Column|Non-Null Count|Dtype|
|---  |------|--------------|-----|  
 0  | artist            |17996 non-null  |object  
 1   |track             |17996 non-null  |object  
 2   |popularity        |17568 non-null  |float64 
 3   |danceability      |17996 non-null  |float64 
 4   |energy            |17996 non-null  |float64 
 5   |key               |15982 non-null  |category
 6   |loudness          |17996 non-null  |float64 
 7   |mode              |17996 non-null  |category
 8   |speechiness       |17996 non-null  |float64 
 9   |acousticness      |17996 non-null  |float64 
 10  |instrumentalness  |13619 non-null  |float64 
 11  |liveness          |17996 non-null  |float64 
 12  |valence           |17996 non-null  |float64 
 13  |tempo             |17996 non-null  |float64 
 14  |duration_ms       |17996 non-null  |float64 
 15  |time_signature    |17996 non-null  |category
 16  |class             |17996 non-null  |category

## Conclusion
The best model is RandomForest with ROC AUC one-vs-rest score 0,875612.