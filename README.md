# Predicting-the-Price-of-Bitcoin-Using-Deep-Learning.
It was noted during training that the higher the batch size (200), the worst the prediction on the test set. 
We have used 50 epochs to train out LSTM model with batch size 150, we have also tried 60,70, 90 and 100 epochs but we didn’t get any significant result.
We have used 1,3 and 4 LSTM Layers for training our model but best result comes at using 1 LSTM Layer.
In univariate case, the best result will come at at training of LSTM layer with 6 neurons.
In multivariate case, the best result will come  at training of LSTM layer with 100 neurons.
Using deep neural networks, has provided us with a better understanding of Bitcoin, and LSTM architecture.


Results using single variable approach (univariate)

MSE on normalised training data is:
0.07554651699763121
MSE on  normalised testing data is:
0.07554651699763121

Results using multivariate approach :
MSE on normalised training data:
0.011512494197501335

MSE on  normalised testing data:
0.18213032776285212
