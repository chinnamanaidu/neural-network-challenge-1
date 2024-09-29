####  neural-network-challenge-1

##  NEURAL NETWORKS PROGRAMMING

## Introduction
In this challenge the student loan CSV file is successfully loaded and credit rating is taken as y attribute, the scalar API used to get the xtrain scaled, x test scaled and also to get xtrain and ytrain and test data

Sequential model is used to build the Neural Networks and Tensorflow Keras model to build the Dense layers using Relu and Sigmoid activation is used for the analysis, the prediction scores are almost 75% provides good prediction strategy to predict the loan approvals 

#### Read the csv into a Pandas DataFrame
#### Review the DataFrame
#### Review the data types associated with the columns
#### Check the credit_ranking value counts
#### Define the target set y using the credit_ranking column
#### Display a sample of y
#### Define features set X by selecting all columns but credit_ranking
####  Review the features DataFrame
####  Split the preprocessed data into a training and testing dataset
####  Assign the function a random_state equal to 1
####  Create a StandardScaler instance
####  Fit the scaler to the features training dataset

##  Step 1: Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer using Tensorflow’s Keras

####  Define the the number of inputs (features) to the model
####  Review the number of features
####  Define the number of hidden nodes for the first hidden layer
####  Define the number of hidden nodes for the second hidden layer
####  Define the number of neurons in the output layer
####  Create the Sequential model instance
####  Add the first hidden layer
####  Add the second hidden layer
####  Add the output layer to the model specifying the number of output neurons and activation function
####  Display the Sequential model summary

##  Step 2: Compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.

####  Compile the Sequential model
####  Fit the model using 50 epochs and the training data

##  Step 3: Evaluate the model using the test data to determine the model’s loss and accuracy.

####  Evaluate the model loss and accuracy metrics using the evaluate method and the test data
####  Display the model loss and accuracy results

##  Step 4: Save and export your model to a keras file, and name the file `student_loans.keras

####  Set the model's file path
####  Export your model to a keras file
####  Set the model's file path
####  Load the model to a new object

## Predict Loan Repayment Success by Using your Neural Network Mode

####  Set the model's file path
####  Load the model to a new object
####  Make predictions with the test data
####  Display a sample of the predictions
####  Save the predictions to a DataFrame and round the predictions to binary results

## Display a classification report with the y test data and predictions

###  Print the classification report with the y test data and predictions

## describe the predictions
1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

These are the data required for student loan
payment_history           
location_parameter        
stem_degree_score
gpa_ranking               
alumni_success            
study_major_code          
time_to_completion        
finance_workshop_score    
cohort_ranking            
total_loan_score          
financial_aid_score       
credit_ranking       

All the above column plays critical role for X train and also to get the scaled data for X_test_scaled and y_test
The abov Sequential NN model provides the accuracy score of around 75% accurate would recommended model for student loan
                 

Based on the data you chose to use in this recommendation system,
would your model be using collaborative filtering, content-based filtering,
or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

Collaborative filtering is more recommended since it has diversed data set to train the model and also to improve the accuracy score

The content based filering is not recommended is more specific to user profile and his own interested could not be relevant to build
the model.

Describe two real-world challenges that you would take into consideration
while building a recommendation system for student loans. Explain 
why these challenges would be of concern for a student loan recommendation system.

The sequential Model and Dense layer filtering using (Relu, Sigmoid) recommendations provides more level of accuracy so a dashboard
gets the users input and predicts it could be approved or not before the loan officer reviews and approves the loan.

