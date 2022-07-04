# week17challenge


##Overview of the analysis


  - use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling to predict credit risk.



##Results


  -Naive Random Oversampling result: The balanced accuracy score was 65%, 1% of the precision for high risk with 63% of recall. 
  <img width="826" alt="截屏2022-07-04 上午12 49 40" src="https://user-images.githubusercontent.com/100896537/177083507-48d1f5e6-5cd0-4ea9-ab37-fe08a56b1742.png">
  
  
  -SMOTE Oversampling result: The balanced accuracy score was 65%, 1% of the precision for high risk with 64% of recall.
  <img width="674" alt="截屏2022-07-04 上午12 53 13" src="https://user-images.githubusercontent.com/100896537/177083812-eefbd813-3203-4912-b677-78464c2afccd.png">
  
  
  - Under sampling result: The balanced accuracy score was 53%, 1% of the precision for high risk with 61% of recall.
  <img width="783" alt="截屏2022-07-04 上午12 54 07" src="https://user-images.githubusercontent.com/100896537/177083899-38d18e33-ef22-4b01-876a-ba35a2cac767.png">
  
  
  - Combination (Over and Under) Sampling result: The balanced accuracy score was 62%, 1% of the precision for high risk with 60% of recall.
  <img width="777" alt="截屏2022-07-04 上午12 55 31" src="https://user-images.githubusercontent.com/100896537/177084037-7991917b-991b-44ff-9fe8-977b02315800.png">
  
  
  - Using the Balanced Random Forest Classifier: The balanced accuracy score was 82%, 3% of the precision for high risk with 75% of recall.
  <img width="782" alt="截屏2022-07-04 上午12 57 09" src="https://user-images.githubusercontent.com/100896537/177084200-3bcc9e61-698d-41aa-a248-987ae2f82462.png">
  
  
  - Using the Easy Ensemble AdaBoost Classifier: The balanced accuracy score was also 82%, 3% of the precision for high risk with 75% of recall.
<img width="779" alt="截屏2022-07-04 上午12 58 01" src="https://user-images.githubusercontent.com/100896537/177084271-4cf1a9c3-4260-4fdc-8d44-db4631868385.png">


  
 






##Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


  The balanced random forest classifier and easy ensemble adaboost classifier has retured similar results after sampling, with the highest balanced accuracy score at 82%, and the precision score was 3% for high risk, and with 74% of recall score. Ensemble classifier resample the data to determine which of the credit card are low or high risk, while others determine which credit card are with the higher risk.
  
  Since the ensemble classifiers have the highest accuracy scores, they are recommended. 
