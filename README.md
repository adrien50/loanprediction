# Loan Eligibility Prediction using Gradient Boosting Classifier

##  Problem statement 
SYL bank is one of Australia's largest banks. Currently, the loan applications which come in to their various branches are processed manually. The decision whether to grant a loan or not is subjective and due to a lot of applications coming in, it is getting harder for them to decide the loan grant status. Thus, they want to build an automated machine learning solution which will look at different factors and decide whether to grant loan or not to the respective individual.

In this ML problem, we will building a classification model as we have to predict if an applicant should get a loan or not. We will look at various factors of the applicant like credit score, past history and from those we will try to predict the loan granting status. We will also cleanse the data and fill in the missing values so that our ML model performs as expected. Thus we will be giving out a probability score along with Loan Granted or Loan Refused output from the model.

## Project flow
* In depth exploratory data analysis of each feature & Feature engineering
* Imputing missing data with soft impute
* Binarizing the Target variable with LabelBinarizer() function
* Scaling the independent variables
* Training and testing the model using Cross Validation
* Creating custom functions for Machine Learning Models
*  Create function to find which features are more important than others through model
* Create model to  predict the ROC curve for various models and finding the best one
* Finding accuracy and feature importance using XGB classifier
* Building statistical models like Gradient Boosting, XGBoost, etc
* Using SMOTE for Data Balancing
* Creating pickle files for model reusability

## Result

Macro Economic Indicators did not help in prediction of weekly sales. The sales data is very similar over different years 
and this consistency helped to predict the sales. 



