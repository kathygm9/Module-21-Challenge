# Module-21-Challenge

Neural Network Model Report 

**Purpose of the analysis**
 The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not
applicants for funding will be successful. With knowledge of machine learning and neural
networks, we must use the features in the provided dataset to create a binary classifier that is
capable of predicting whether applicants will be successful if funded by Alphabet Soup

**Data Preprocessing**

What variable(s) are the target(s) for your model?

*The target variable for the model was labeled “IS_SUCCESSFUL” and has the value of 1 for yes and 0 for no.*

What variable(s) are the features for your model?

*The remaining columns were to be considered features for the model*

What variable(s) should be removed from the input data because they are neither targets nor features?

*Several data points as a cutoff to bin “rare” variables together with the new
value of “Other” for each unique value.*

**Compiling, Training, and Evaluating the Model**

How many neurons, layers, and activation functions did you select for your neural network model, and why?

*There were three layers total for each model after applying Neural Networks.*

Were you able to achieve the target model performance?

*6,461  parameters were created by a three-layer training model. The first attempt was just over
73% accuracy close to 75%.*


**Summary**

After dropping EIN and NAME the remaining columns were to be considered features for the model. Name was added back into the second test for binning purposes. The data was then split for training and testing sets. APPLICATION data was analyzed and “CLASSIFICATION value was used
for binning. Categorical variables were encoded by get_dummies()
after checking to see if the binning was successful.

Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)


 



