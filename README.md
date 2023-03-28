# Stock Returns 
Built a neural network to predict the stock market using purely historical data. Used a Recurrent Neural Network (RNN) and a Long Short-Term Memory (LSTM). The conclusion is that using historical data isn't good enough to yield good results. Feel free to dive into the notebook, if you want to see how the other models performed.


LSTM performed relatively well using one step forecast. However, one step forecast is not really that useful on this scenario since I only used the adjusted values. And even though, it looked like it did quite well, it couldn't predict the peak towards the end which indicated that this model more suitable for more stable stocks.
![LSTM](https://user-images.githubusercontent.com/79936222/140310997-1c58f1b7-914e-44e7-8980-faa365c147bf.jpeg)


On the other hand, here the LSTM model did't predict anything, only next value after the first one and remained the same afterwards.
![multistep-LSTM](https://user-images.githubusercontent.com/79936222/140312796-6e81c63f-4fc4-4520-94fd-5a019b9d435d.jpeg)
