
## **Project Overview**

Stock price prediction plays a crucial role in financial markets, and accurate forecasts can have significant implications for businesses, investors, and financial institutions. 

Stock price prediction helps investors and fund managers make informed investment decisions. By accurately forecasting future stock prices, investors can identify potential opportunities for maximizing profits or minimizing losses. It enables them to allocate their capital wisely and adjust their investment portfolios based on predicted price movements.

Machine and Deep Learning have demonstrated their potential to enhance stock price prediction accuracy and assist investors, traders, and financial analysts in making informed decisions. By leveraging ML techniques, businesses can gain valuable insights, optimize investment strategies, and improve risk management in stock market's complex and dynamic realm.

The prediction of stock prices is a challenging task due to the inherent complexity and volatility of financial markets. Traditional methods often fail to capture the intricate patterns and dependencies present in stock price data. However, RNN and LSTM models have shown great potential in capturing temporal dependencies and making accurate predictions in various time series forecasting tasks.


In this project, we will focus on implementing recurrent neural networks (RNNs) and long short-term memory (LSTM) networks specifically for the task of stock price prediction. This project serves as an essential foundation for understanding and utilizing these advanced deep learning techniques in the context of financial forecasting.


## **Execution Instructions**
<br>
**Python Version: 3.8.10**

* Create a python environment using the command 'python3 -m venv myenv'.

* Activate the environment by running the command 'myenv\Scripts\activate'.

* Install the requirements using the command 'pip install -r requirements.txt'

* Run engine.py with the command 'python engine.py'.
 
 ## **Disadvantages of RNN**

 * Even though RNNs are quite powerful, they suffer from Vanishing gradient problem which hinders them from using long term information, like they are good for storing memory 3-4 instances of past iterations but larger number of instances don't provide good results so we don't just use regular RNNs. Instead, we use a better variation of RNNs: Long Short Term Networks(LSTM)