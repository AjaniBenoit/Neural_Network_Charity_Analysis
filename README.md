# Neural_Network_Charity_Analysis
Machine learning and neural networks

## Project Overview

Utilizing neural networks to create a binary classifier that is capable of predicting wheter applicants will be successful if funded by Alphabet Soup. 

The initial CSV file contained 34,000 organizations that have received funding from Alphabet Soup over the years. 

### Results 

#### Data Preprocessing 

•	The EIN and Name columns have been removed from the input data as they contain identifiers. 
•	The IS_SUCCESSFUL columns contains binary data referring to whether or not the donations were used effectively. IS_SUCCESSFUL is the target for the deep learning neural network. 
•	The APPLICATION_TYPE; AFFILIATION; CLASSIFICATION; USE_CASE; ORGANIZATION; STATUS; INCOME_AMT; SPECIAL_CONSIDERATIONS; and ASK_AMT are features for our mode. 

#### Compiling, Training, and Evaluating the Model 

•	The deep-learning neural network model has two hidden layers. The first hidden layer has 80 neurons with a sigmoid activation. The second hidden layer has 20 neurons with a relu activation. 
![fig1.png](https://github.com/AjaniBenoit/Neural_Network_Charity_Analysis/blob/main/fig1.png)

•	The model’s accuracy is under 75 percent and does not help predict the outcome of the charity donation. 

### Summary 

The deep learning neural network model did not reach the target of 75 percent accuracy and does not predict the outcomes of charity donation. 


