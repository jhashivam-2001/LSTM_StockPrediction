# LSTM_StockPrediction
<hr style="border:2px solid gray"> </hr>
The stock price for a day will depend upon:

* The trend that the stock has been following in the previous days, maybe a downtrend or an uptrend.
* The price of the stock on the previous day, because many traders compare the stock’s previous day price before buying it.
* The factors that can affect the price of the stock for today. This can be a new company policy that is being criticized widely, or a drop in the company’s profit, or maybe an    unexpected change in the senior leadership of the company.
<hr style="border:1px solid gray"> </hr>
These dependencies can be generalized to any problem as:

* The previous cell state (i.e. the information that was present in the memory after the previous time step).
* The previous hidden state (i.e. this is the same as the output of the previous cell).
* The input at the current time step (i.e. the new information that is being fed in at that moment).
<img src="https://cdn.analyticsvidhya.com/wp-content/uploads/2017/12/10131302/13-768x295.png">

For the stock prices datasets I have used the __"nsepy"__ library which can be installed as :

---
pip install nsepy
---

__To specify a particular company for fetching it's stock prices you need to specify the symbol of the company as listed on the NSE.__
