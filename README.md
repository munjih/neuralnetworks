# AlphabetSoupChallenge

Neural network learning model was built on the Alphabet soup funding data in order to aid in determining future decisions. After preprocessing, the data ended up with 42 input features so initially chose one hidden layer, 84 neurons and 'relu' as the activation function for the model. This condition was chosen to keep the model simple with one hidden layer and use 2-3x of neurons per input feature. The data is nonlinear so started with 'relu'. Performance accuracy was under 70% in the initial round.

In order to improve performance, tested adding second and third layers, as well as changing the number of neurons and the activation function to 'tanh. Also, tested dropping additional input features such as "Status" and "Special considerations", which led to increase in performance. The final model predicts the test data at 73%. The model has three hidden layers each with 100, 70, 40 neurons and use 'tanh' as the activation function. Increasing epoches did not improve the accuracy so kept it at 50. 

Finally, the performance was compared with Random Forest classification, which is a simple but strong algorithm for nonlinear classification. The accuracy of Random Forest was 71%, thus the neural network model outperformed Random Forest bt 2%.
