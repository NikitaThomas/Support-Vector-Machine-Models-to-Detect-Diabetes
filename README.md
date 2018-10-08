# Support-Vector-Machine-Models-to-Predict-Diabetes

This project conducts exploratory analysis on the Pima Indains Diabetes dataset obtained from the National Institute of Diabetes and Digestive and Kidney Diseases. 

### Attribute Information: 
 
* PREG- number of times pregnant
* PLAS- Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* PRES- Diastolic blood pressure (mm Hg)
* SKIN- Triceps skin fold thickness (mm)
* INSU- 2-Hour serum insulin (mu U/ml)
* MASS- Body mass index (weight in kg/(height in m)^2)
* PEDI- Diabetes pedigree function
* AGE- Age (years)
* CLASS- Class variable (0 or 1)

Support Vector Machine models were fit onto the training dataset and used to predict on the testing set in order to classify whether the patient was diabetic (class=1) or not (class = 0). The sci-kit learn package was utilized to perform both rbf kernel (with parameter tuning on C and gamma) and polynomial kernel (with parameter tuning on C and degree) SVMs. The prediction accuracy, confusion matrix, and area under the ROC curve are recorded for each model. 
