# Deep_Learning_Challenge
Module21_ Assignment  Deep_learning_challenge

#### By _**Navyasri Pusuluri**_

## Tools Used

* _Google collaborate_
* _Git Bash_

## Modules Used

* _sklearn.model_selection_
* _sklearn.preprocessing_
* _pandas_
* _tensorflow_

## Details of Assigments.

* All the analysis can be found at  main level below path Deep_learning_challenge.

## Report on the Neural Network Model

* overview of the Analysis: 

        The goal of this Alphabet Soup project is to create an algorithm using machine learning and neural networks to predict whether applicants will be successful if funded by the fictional non-profit foundation.

* Result of the Analysis:

    * Data Preprocessing:

        * Target variable = IS_SUCCESSFUL.. 1 is consider as yes(successfull) and 0 is consider as no (not successfull).
        * Features = All other columns.
        * Removed the two non-beneficial columns from the dataset that is "EIN", "NAME".

    * Compiling, Training, and Evaluating the Model:

        * Attempt1:
            * Application_type cutoff = 600
            * classification cutoff= 300
            * layer1= 9, activation = relu
            * layer2= 18, activation = relu
            * loss: 0.5583 , accuracy:0.7250
            * A loss value of 55 indicates that model can be futher optimized.
            * The accuracy percent shows that 72% of the model's perdicted values of align with the true values in the original data set.
            * Time taken to run the train model is 3m.
        * Attempt2: Adding hidden layer
            * Application_type cutoff = 600
            * classification cutoff= 300
            * layer1= 9, activation = relu
            * layer2= 18, activation = relu
            * layer3= 27, activation = relu
            * loss: 0.5587 , accuracy:0.7243
            * A loss value of 55 indicates that model can be futher optimized.
            * The accuracy percent shows that 72% of the model's perdicted values of align with the true values in the original data set.
            * Time taken to train the model is 2m.
        * Attempt3: Chaning the activation function    
            * Application_type cutoff = 600
            * classification cutoff= 300
            * layer1= 9, activation = relu
            * layer2= 18, activation = tanh
            * layer3= 27, activation = tanh
            * loss: 0.5562 , accuracy:0.7247
            * A loss value of 55 indicates that model can be futher optimized.
            * The accuracy percent shows that 72% of the model's perdicted values of align with the true values in the original data set.
            * Time taken to run the train model is 2m.
    * Summary:

            * In this three attempts, the model was unable to achieve a target predictive accuracy higher than 72.5%. Hypertuning resulted in virtually no improvement. I would consider using another classification model to see if it is better at predicting whether applicants will be successful if funded by Alphabet Soup.

            

