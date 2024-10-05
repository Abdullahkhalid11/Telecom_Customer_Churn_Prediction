# Telecom_Customer_Churn_Prediction
Case Study: Predicting Customer Churn in a Telecom Company
This dataset is about the people who will keep telecom services(Not Churn) and leave the Telecom company (Churn) based on the inputs and services of that company.  
It was a much-cleaned dataset with 7043 observations and 21 features. 
Only one column has missing values So I impute these missing values The dataset doesn’t contain any outliers I faced challenges during encoding. As I have observed the repetition of the no service provider category in the 6 consecutive columns with the same values.So we deal with it. 
I have Implemented Three Machine learning classification Algorithms (Random forest classifier, Naïve Byes and KNN) and compared their prediction outputs.  
I have found that the Model accuracy of the Random forest classifier after Hyperparameter tuning is the highest(80.2%), followed by KNN with 79% accuracy and Naive Bayes has the lowest model accuracy which is 73.45%. 
The lowest accuracy of Naive Bayes is due to the high cardinality of the Dataset and due to the Imbalance of the Output Churn feature.
