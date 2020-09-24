# Alphabet Soup Challenge

## Summary

How many neurons and layers did you select for your neural network model? Why?
- The neural network model contains a count of 167 input features. The neurons total to six, four in the first hidden layer, and two in the second hidden layer. The decision to use this amount of neurons and layers came through a process of trial and error along with the knowledge of knowing the performance of using a deep neural network. Initially the model was ran with more neurons but soon found that so many neurons were not necessary and that the model performed with almost identical results with less neurons. 

Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
- The model's accuracy score resulted in 75.8%, which reached the target model. To achive this model performance the process of bucketing the "NAME" feature, which contained many unique values that could be grouped as "Other". This created more features for the model to train on. It was then necessary to use OneHotEncoder for each feature then to scale the the training dataset. Choosing the Relu activation for the hidden layers and Sigmoid for the input increased the model's performance. 

If you were to implement a different model to solve this classification problem, which would you choose? Why?
- Random Forest modeling could also be used. The data is tabular, which would work well with this type of model. The amount of features available in the dataset would allow for tree depth that will potentially provide similar accuracy to the deep neural network.
