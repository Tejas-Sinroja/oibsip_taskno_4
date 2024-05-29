# Email spam detection 
Here the task is to train a machine learning model that can learn from the past mail data and classify them into the two category(spam or ham)

## workflow :

1. Data Acquisition : The email data consist 5572 samples of mails with 5 columns. Where there is v1 named column is the target column.
2. Data preprocessing : Removing unnecessary columns , Renaming the other columns with apropriate names and encoding the class variable(into numerical).
3. Data splitting & Data modeling : Splitting the data into the 70/30 ratio for traning and testing and using countvectorizer to convert text string into the suitable format for training.
4. Model training : model that are used here :  
   Multinomial Naive bayes classifier  
   Logistic regression  
   Decision tree classifier  
   Random Forest classifier  
   Support vector machine classifier  

5. Result : By finding the accurracy score, confusion matrix and classification report for all the mentioned classifier the best fit model is Multinoimial naive bayes classifier with the accuracy score : 0.9880
