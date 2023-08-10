# Disease Predection Using ML
 
This project aims to develop a robust machine learning model for predicting human diseases based on their symptoms. The approach involves several key steps:

### Data Collection: 
The initial step is gathering data, and for this purpose, a Kaggle dataset is used. This dataset contains two CSV files: one for training and another for testing. It comprises 133 columns, with 132 columns representing symptoms and the last one indicating the prognosis.

### Data Cleaning: 
Data cleaning is crucial to enhance model quality. In this dataset, all columns are numerical, except for the target column "prognosis," which is string-based. To address this, the prognosis is encoded into numerical values using a label encoder.

### Model Training: 
With clean data in hand, machine learning models can be trained. The Support Vector Classifier, Naive Bayes Classifier, and Random Forest Classifier are employed in this project. Model quality is assessed using a confusion matrix.

### Inference: 
The article employs a combined approach for prediction. By leveraging the predictions from all three trained models, the final disease prediction becomes more accurate and robust.

In conclusion, the article presents a function that accepts symptom inputs separated by commas. This function uses the trained models to predict the disease based on the symptoms and returns the predictions in JSON format.
