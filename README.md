# deep-learning-challenge
The analysis is trying to predict the success of applicants funded by Alphabet Soup using a deep learning model. The process involves data preprocessing, including dropping non-beneficial columns and binning values in certain columns, and building, compiling, training, and evaluating a neural network model.
Results:
•Data Preprocessing
    •	IS_SUCCESSFUL is the target variable for the model.
    • All other columns other than target variable are Feature Variables
    •	'EIN' and 'NAME' were removed from the input data as they are neither targets nor features.
•Compiling, Training, and Evaluating the Model
    •	I chose two hidden layers and activation functions with 80 neurons in the first layer and 30 in the second layer in order to find the 
      highest performacnce. 
    • I was not able to achieve the target model performance. I made multiple attempts at changing the different variables. 
    • In order to incerease the model performance I binned values, dropped more values, and adjusted the number of neurons. 
Summary
    • The deep learning model had modest results in predicting the success of applicants. Adjusting the different variables, remvoing unncessary data, and binning may help optimize the model. Alternative models could lead to improved predictive performance. 
