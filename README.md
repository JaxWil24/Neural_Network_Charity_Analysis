# Neural Network Charity Analysis

## Overview
* This analysis was to predict successful charities if they were funded by Alphabet Soup.

## Results
Data Preprocessing:
* The column "Is_Successful," would be considered the target for this model.
![image](https://user-images.githubusercontent.com/106329824/195593143-c59e8850-e04a-44ba-a3dc-f5e01dfd22d4.png)

* Application type would be considered a feature in this model.
* Columns "EIN," and "NAME," are neither targets nor features, and can be removed from the input data. 
![image](https://user-images.githubusercontent.com/106329824/195592991-bf401167-13c7-4f93-83ee-02b61fe3e04e.png)

Compiling, Training, and Evaluating the Model:
* Ending with 2 layers, activation relu and sigmoid, this model did not improve. Editing one feature at a time, I saw no change, or a decrease in accuracy of the model.
![image](https://user-images.githubusercontent.com/106329824/195593216-9fbeae45-51f5-4dca-aad7-21e03cb02b82.png)
* With the target being 75% accurate, and the model not reaching above 72.8%, I was not able to achieve the target model performance.
*  The efforts to create more efficiency are adding more layers, taking a layer away, changing the type of scaler, changing the types of activations, and changing the number of epochs.
![image](https://user-images.githubusercontent.com/106329824/195593346-53d85e84-9259-44a3-832b-0867dc3f795d.png)

## Summary
* Overall, the model was successful. With over 70% accuracy, this model would be able to give some information on which charities would succeed.
* Any binary logistic regression would satisfy this analysis. This type of model is used for two outcomes, and this prediction is to determine if the charity will or will not be successful.  
