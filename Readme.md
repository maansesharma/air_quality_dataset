#AIR QUALITY CODE - REGRESSION MACHINE LEARNING MODEL
#ELECTRIC VEHICLE CODE - CLASSIFICATION MACHINE LEARNING MODEL 
#AIM : 
 This dataset includes regression model which predicts air data value which shows region which are affected the most by help of clustering another dataset, includes the classification of eligibility of vehicles on basis of certain parameter for a policy made by governent. 


#AIR QUALITY CODE: 
 ##MODEL USE: Linear Regression, Random Forest regression, Kmean

##DESCRIPTION:
 The main idea behind analysis of this dataset is to analyse the data value and predicting. 

 The data value predicted is use to understand pollution trend over time with season , year and region. Data Preprocessing is done with One-Hot Encoding and cleaning null value , duplicate value and drop null value. 
For the data value prediction Linear Regression , Random Forest regression is applied where means square error in linear regression is 26.25 , r2 score is 0.7435  hence,  
Random Forest regression gave mean square error is 19.89 and r2 score is 0.804. 
 
The residual for this regression is near Zero which means the error is near zero and prediction is perfect. Also , Kmeans is performed in order to know cluster of region affected the most.

#ELECTRIC VEHICLE CODE:

##MODEL USE:  Logistic Classifier  , KNN 
##DESCRIPTION:
 The main idea behind the dataset is to analyse the eligibility of vehicle based on columns such as 'model' , 'electric ange' , 'make' , 'model year' , 'electric vehicle type'. 

For This LabelEncoding is done and certain values are drop so that the dataset convert into 'integer' value. This dataset is analyzed with model 'Random Forest Classifier' and 'KNN'. It give accurate prediction model based on the target value.  


#To install all the dependencies kindly run : "pip install -r .\requirments.txt"


