# Credit_Card_Fraud_Detection
Here we are going to predict the fraudulent value from the data which we get from kaggle 
## IMPORTANT REQUIREMENT
1. DATASET:-

  * Download data form KAGGLE:-https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
  * the data is in the perfect form means (the feature are extracted using Principal Componemt Analysis). 
 
2. IMPORTANT TOOLS:-
  * NUMPY
  * PANDAS
  * SKLearn
 ## WORKING
 1. we are using the pre_train model which uses the PCA as the important feature of the data is already extracted.
 2. Then we apply some preprocing step to clean the data accoding to the model like uding the drop feature or removingg hte duplicate element .
 3. As the difference is very high between the minimum value and the maximum value so we use the min_max_scalar or standard scalar(normalize the data).
 4. After this we split oue data into 2 parts training and testing .with the ratio of 70% and 30%.
 5. After cleaning the data we apply different algorithm for aur model like logistic regression
 6. Then we calculate the precision,recall, F1 score using confusion matrix(Heat Map).   
