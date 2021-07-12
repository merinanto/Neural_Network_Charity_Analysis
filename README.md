# Neural_Network_Charity_Analysis

## Overview of the Analysis

The purpose of the analysis is to implement Deep Neural Network machine learning techniques to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

Analysis is done on the dataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years:-
https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/Resources/charity_data.csv

## Results

### Scripts  Used for Analysis

1. Script used to implement the Deep Neural Network on the dataset:-
https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity.ipynb

2.Script used to optimize the Deep Neural Network on the dataset:-
https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimzation.ipynb

### Details of Analysis 

- Target Variable :- IS_SUCCESSFUL

- Features :- APPLICATION_TYPE,AFFILIATION,CLASSIFICATION,USE_CASE,ORGANIZATION,STATUS,INCOME_AMT,SPECIAL_CONSIDERATIONS

- NON Target-Features :- EIN,NAME(Identification Column)

- No of HIDDEN LAYERS -2

- No of Neurons on first Hidden Layer-20

- No of Neurons on first Hidden Layer-13 

- Not able to required performance 

  ![image](https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/Resources/performance_values.png)

#### Optimization Details

1. Removed the status feature as only 5 inactive organization
   Loss got reduced, but very slight increase in Accuracy
   
   ![image](https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/Resources/NOISY_VARIABLE.png)
   
2. Increased the number of Neurons.
   But loss got increased and performance degraded.
   
   ![image](https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/Resources/added_neuron.png)
   
 
 3. Added another hidden layer is added.
    Loss got reduced, but very slight increase in Accuracy
    ![image](https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/Resources/added_hidden_layer.png)
    
 4. Changed activation function  in the first hidden layer.
    But loss got increased and performance degraded.
    ![image](https://github.com/merinanto/Neural_Network_Charity_Analysis/blob/main/Resources/changed_activation_function.png)
    
  
  ## Summary of the Analysis
  
  1. Loss and performance is not very good for the anaysis
  
  2. One of the reason can be some features may be confusing the model
  
  3. As an alternate tradional classifiers can be tested.
 
  4. Looks like overfitting causing the issues.
  

 
   

