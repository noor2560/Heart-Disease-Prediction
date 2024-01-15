# Heart-Disease-Prediction
 Predicting heart disease via machine learning involves gathering diverse health data, preprocessing it, selecting features, training models like logistic regression, and evaluating their accuracy. The goal is to deploy a reliable tool for real-time identification and prevention in clinical settings.

Step 1: Import libraries (numpy, pandas, sklearn- Model selection, Linear model, Metrics)

Step 2: Data-preprocessing
Data source: Heart disease dataset is accessed from Kaggle website. Load the dataset using pd.read_csv function.
Data cleaning: Dataset which have unnecessary data, incomplete data, discrete data or null data are analysed and discarded to obtain a clean complete dataset for further processing.

Step 3: Training and testing data
This resulting data split into 80% train and 20% test data, which was further passed to the  Logistic Regression model to fit, predict and score the model.  

Step 4: Model training
Have used Logistic regression model, Decision tree classifier and Random forest classifier.

Step 5: Building predictive system
Input is fed to model.predict() function.
If outcome is '0', the Person does not have a Heart Disease
else, the Person has Heart Disease.

Confusion matrix is plotted and accuracy scores are measured.



