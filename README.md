# PRML-Assignment-2

**Q2 Part E**

we implemented keras sequential model with one input, one hidden and one output layer for the given task.

We tried 3 activation function, ReLu, Sigmoid and tanh.Sigmoid and tanh performed poorly, but tanh gave a descent performance in comparison to other to activation function, which can be explained through the given data trend.
![WhatsApp Image 2021-11-28 at 11 38 48 PM](https://user-images.githubusercontent.com/64272528/143781589-a7c2580c-263b-4115-a2cd-e10475e35894.jpeg)


We used only one hidden layer, because it was a simple dataset.  More hidden layer couldoverfit the data.We tried different combinations of neuron units in hidden layer and we got the best resultwith the 70 neuron units.

We used 5000 epochs with early stopping function and learning rate scheduler parametertop avoid the overfitting.

Final mean square error on the complete dataset obtained is: 108.63. 

Mean square error obtained by the non linear function given in the question is: 76.12So, we can conclude that our model is a good approximation on the given dataset.


**Q2 Part F**

We coded backpropagation algorithm for a FFN (consisting one input layer, one hidden layer and one output layer) from scratch.

here we implmented the algorithm with batch size of 1.

as we can see from the output, our model trained poorly as our optimizer is stochastic gradient descent. we also saw in E part that despite having advances optimizer like ADAM our model perfromed decently.

**Q3**

Using the decision tree classifier, we get almost similar decision surface for k=5 and k=100, due to random function, we get different decision surface boundary, but after running, multiple times, we get the the test accuracy as 0.8 for both the cases.




