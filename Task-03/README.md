○ Task objective 

 Build a model to predict whether a person is at risk of heart disease based on their health data. 
 
○ Dataset used 
 Heart Disease UCI Dataset (available on Kaggle) 
 
○ Models applied 
Logitic Regression 
 
○ Key results and findings:
### Model Performance

A Logistic Regression model was trained to predict heart disease risk using selected clinical features.

The model achieved an accuracy of approximately 76%, indicating a good overall prediction capability.

The ROC–AUC score of 0.83 shows that the model has a strong ability to distinguish between patients with and without heart disease.

### Confusion Matrix Insights

The model correctly identified 125 patients with heart disease and 85 healthy individuals.

However, 32 patients with heart disease were misclassified as healthy, which highlights the importance of further improving sensitivity in medical applications.

False positives were present but are generally less critical than false negatives in healthcare scenarios.

### Important features affecting presidtion
Key contributing factors include age, maximum heart rate, and ST depression. Overall, the model demonstrates good potential for early risk detection.

