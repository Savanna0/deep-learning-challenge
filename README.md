# deep-learning-challenge

## Overview
In this module, we were tasked in creating a machine learning tool that can help select applicants for funding with the best chance of success in their ventures.

## Results
### Data Preprocessing

- What variable(s) are the target(s) for your model?
  - Using the dummies Data Frame, I took the column IS_SUCCESSFUL and made these values into the target variable.

- What variable(s) are the features for your model?
  -Also using the dummies Data Frame, I took dropped the IS_SUCCESSFUL column and used all the remaining columns as the feature variables.

- What variable(s) should be removed from the input data because they are neither targets nor features?
  - I dropped the columns EIN and NAME from the data because they were neither targets nor features.
    
### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - There are two hidden layers and one output layer. In the first hidden layer, there are 80 neurons. In the second hidden layer, there are 30 neurons. And in the output layer there are 1 neuron.
![Screen Shot 2024-11-17 at 6 37 49 PM](https://github.com/user-attachments/assets/e1ed38ab-fc40-4357-a9da-941c0b31e230)

  
- Were you able to achieve the target model performance?
    - No, I was only able to achieve 73% for for the model.
![Screen Shot 2024-11-17 at 6 39 12 PM](https://github.com/user-attachments/assets/c91eeba9-622e-4844-9c10-dbe102b6dee8)


- What steps did you take in your attempts to increase model performance?
  - I changed the number of hidden layers to three with no change. Then I attempted to change the number of neurons for both of the hidden layers with no significant change. 
  
## Summary

The overall results show that the accuary is significant enough to use when looking for best chance of success in their ventures. Maybe adding more to the data would help acheive the target goal. 
