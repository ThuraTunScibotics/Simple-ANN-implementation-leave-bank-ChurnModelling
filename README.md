# Simple-ANN-implementation-leave-bank-ChurnModelling

## Project Description
This is just the simple implementation of Artificial Neural Network classification on customer will LEAVE (1) the bank or NOT LEAVE (0).

## Dataset
The dataset is provided in the repository as `csv` file.
The features in the dataset - 
* RowNumber          
* CustomerId         
* Surname            
* CreditScore        
* Geography          
* Gender             
* Age                
* Tenure             
* Balance            
* NumOfProducts      
* HasCrCard          
* IsActiveMember     
* EstimatedSalary    
* Exited    

## ANN Architecture and its parameter
* We used 3-Lyer ANN architecutrue with with `units=6` and `activation='relu'`.

## Confusion and Accuracy Score while prediction on 20% data of X_test
The confusion matrix and accuracy score is as follow:
- Actual Leave & Predicted Leave -> 1534
- Actual Leave & Predicted not Leave -> 66
- Actual not Leave & Predicted Leave -> 224
- Actual not Leave & Predicted not Leave -> 176

* Accuracy score is `0.855`

![ann1](https://user-images.githubusercontent.com/70876878/150642140-96cc5c97-3fc6-4851-afed-37f2ebcce8fe.PNG)

## Future work 
* Need to improve the accuracy score
