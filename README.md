# deep-learning-challenge
Report
This analysis was done to do a classification to help Alphabet soup. We are trying to help them create a tool to best allocate there funds whether to be succedssful or not to save them money.
Data Preprocessing

What variable(s) are the target(s) for your model?
  We are trying to target the Is_successful variable
  
What variable(s) are the features for your model?
  Application Type, Affiliation, Classification, Use case, Organization, Status, Income amount, Special considerations and Ask amount.
  
What variable(s) should be removed from the input data because they are neither targets nor features?
  We got rid of Ein and Name variables

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
  hidden_nodes_layer1 = 80
  hidden_nodes_layer2 = 80
  hidden_nodes_layer3 = 70
  hidden_nodes_layer4 = 50
  hidden_nodes_layer4 = 50
  hidden_nodes_layer5 = 50
  I also used a 100 Epochs.
  I tried to use a much bigger data set with a lot more columns. I ended up breaking google colab from using more Ram than i was allowed. from there i scaled it way down.
Were you able to achieve the target model performance?
  Absolutley not. The 2nd attempt was horrific with litle to no accuracy.
What steps did you take in your attempts to increase model performance?
  I tried to take away more columns for accuracy and keep the same level of epochs, I also tried to increase the amount of Hidden layers. I think that was useless in the end
  
