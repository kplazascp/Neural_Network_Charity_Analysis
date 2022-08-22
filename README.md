# Neural_Network_Charity_Analysis

## Overview of the analysis
In this analysis we are helping a Non-profit organization called Alphabet Soup, which is an organization that helps other organizations to protect the environment, improve people´s well being and unify the world.
We are helping Beck analyze the impact of the donation and vet potential recipients, to ensure that the foundation´s money is being used effectively. This is why, we are helping to predict which organizations are worth donating to, and which are too high risk, to be able to achieve this, we are designing and training a deep learning neural to produce a clear decision making result.

## Results:

### Data Preprocessing
The variables considered for this model were the following:
- IS_SUCCESSFULL as the target for the proposed model
And, for the features of the model:
- APPLICATION_TYPE
- IS_SUCCESSFULL
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_ANT
- ASK_AMT
Also, the varibles considered as no significan columns were:
- EIN
- AFFILIATION

### Compiling, Training, and Evaluating the Model
The first neural network model had 80 neurons in the first layer and 30 neurons in the second.
Also, two hidden layers and relu activation for training, as well a sigmoid for the second.
The result was a Loss of 55.89% and Accuracy of 72.33%

To be able to optimize the model and increase its performance, the columns EIN and AFFILIATION were dropped and a third layer with 10 neurons was added.
Reestablish the Name column and mantain the same variables, as well as three layers of 80 neurons, 30 neurons and 10 neurons accordingly.
For layer one, relu activation for training and for the second and third layer, sigmoid activation.
The Accuracy of the model improved to 78.50% and the loss was of 44.66%

## Summary
We managed to achieve 78% of accuracy, for the target being 75%. To be able to keep improving the model, more combinations of adding/dropping columns and modifying the layers of neurons have to be made. 
