# Alphabet Soup Analysis

For this analysis the 3 models were used for final result. First 2 columns where dropped as these didn’t generated value to the investigation. These were the EID and the Name of each of the organizations. Even though for a different investigation these might be relevant for our analysis they didn’t contribute whatsoever. The classification and transaction type were bucketed as these contained a significant amount of unique values that could affect the models to oversight, hence clusters where created. 

## Neural Network

The first model used after the preprocessing of the data was the Neural Network model. The 75% accuracy amount could not be reached even after modifying the activation methods. It started with the ReLu method for the input and sigmoid for the output. The output layer then was changed to the Tanh model yet no significant change was reflected. The model was tested first with 100 epochs, then with 150 and finally with 200, yet it did not surpass the 73.5% accuracy. 

## Deep Learning

The second model used was the Deep Learning model. Using 2 hidden layers both with an ReLu activation method in the input layer and sigmoid in the output layer. This model was tested with 90 neurons in hidden layer 1 and 10 in hidden layer 2. Again the 75% accuracy could not be reached. The 2 hidden layer activation method was changed to sigmoid, yet the highest accuracy percentage reached 73.5%. Finally the output layer activation method was changed to Tanh and it increased a little to 73.6% accuracy final result. There were no epochs added to the training as after various models tested, there was no significant change in the accuracy percentage.

## Random Forest

Finally, the Random Forest method was tested yet it only reached a 71% accuracy. 

### Conclusion

In the end the Deep Learning model provided the highest accuracy percentage of 73.6% for training and 72.6 for testing. Adding more variables to the Deep Learning model could help reach the desired accuracy percentage, even though adding additional hidden layers could help the model, this could cause the model to be over complicated and the information might be distorted hence the model could fail. It would be best to still use the Deep Learning model but with additional information to be tested and trained.
