# Trading-Strategy
A shallow machine learning model that aims to implement a simple hedging trading strategy and plot the results. The model used to generate buy/sell signals is the K random forest classifier.

The model needs to be trained separately on different stocks and the trading strategy can only consist of a portfolio having one stock

## Results
The plots of the portfolio value and stock value over time have been included in the repository.
The strategy is a hedging strategy. The model does an okay job of avoiding large losses and stops trading when the stock is bearish. However, this strategy is a bit too conservative and the model is unable to capitalise on profit opportunities and lags behind when the stock performs well. As a result, the strategy performs especially well on poor performing stocks.

## Future Improvements
The model is very simple and can be made more complex to improve performance. Using more complex and 'deeper' models like RNNs/LSTMs would definitely yield better results. External factors like S&P 500 and other factors also affect market price movements and should be taken into consideration while trying to implement a trading strategy. The feature engineering can also be improved to generate and use better indicators for trading. 
Intra-day trading could also be implemented to improve profits by increasing the frequencey of trading. Keeping track of price movements every few minutes would significantly increasse the number datapoints and improve the model.



