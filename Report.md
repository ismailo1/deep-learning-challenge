Data Preprocessing

  What variable(s) are the target(s) for your model?

  - The target variable is the 'IS_SUCCESSFUL' column from application_df
  
  What variable(s) are the features for your model?
  - The variables are every other column
  
  What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model
 - EIN and NAME columns should be removed 

 How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The first hidden layer (hidden_nodes_layer1) contains 8 neurons.
- The second hidden layer (hidden_nodes_layer2) contains 5 neurons
- Both hidden layers use the ReLU activation function
 
 Were you able to achieve the target model performance?
 - I was not able to achieve the target 75% performance
 
 What steps did you take in your attempts to increase model performance?
 - I added more layers, removed additional columns and also increased the epochs but could not achieve 75%

Summary: 
The model was able to get to 73% accuracy 
