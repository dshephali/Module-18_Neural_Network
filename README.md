# Module-18_Neural_Network

In this challenge we were tasked with creating a neural network clasiification and prediction model to predict student loan repayment for a a company that specialized in student loan financing. Company would like to be able to predict whether a borrower will repay their loan , so it can provide a more accurate interest rate for the borrower. We created Sequential model using Tensorflow keras which will give 74% accuracy in predicting student loan repayment, based on the data (csv) provided by the company.

Authors & Citation

Shephali Dubey
ChatGPT


Summary

First you import libraries and dependencies, Next, load data from the csv file, then check the data type to ensure the data is numeric and not an object or a string. Also, check the value count to ensure balanced data. Next, preprocess data , define the target datset as Y and rest as X,  Split the data into training and testing set,  normalize the data by using StandardScaler, create a neural network (by assigning an Input layer, 2 hidden layers and an output layer, as well as neurons/units in each layer). Use Tensorflow Keras Sequential model for creating the neural network model. Next, compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric, and predict accuracy and loss scores. Save and export your model to a keras file and then reload and make predictions using testing data. Finally,certain recommendations have been made for student loans recommendation system.
