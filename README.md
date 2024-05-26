# deep-learning-challenge
This assignment involves building a neural network model, divided into five steps:
## 1.	Preprocessing the Data: 
The goal was to transform categorical variables into numerical values. The steps involved:
- Dropping the unnecessary columns (`'EIN' and 'NAME'`).
- Generating a list of categorical variables for each column to determine if there were enough unique values to convert them to numerical form using the nunique() method.
- Reducing the number of unique values for the columns `CLASSIFICATION` and `APPLICATION_TYPE`, grouping less common values into an "Other" category.
- Using the `get_dummies` method to convert categorical variables into numerical ones.
- Splitting the preprocessed data using the `"IS_SUCCESSFUL"` target.
## 2.	Defining the Model: 
We defined our neural network model by specifying the number of input features and the number of hidden nodes for each layer.
## 3.	Compiling the Model: 
We compiled the model to prepare it for training.
## 4.	Training the Model: 
We trained the model using the preprocessed data.
## 5.	Evaluating the Model: 
We evaluated the performance of the trained model.

This structured approach ensures that the data is appropriately preprocessed, the model is correctly defined and compiled, and the training and evaluation steps are systematically conducted for optimal performance.
