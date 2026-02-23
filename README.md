Stock Price Prediction Using Machine Learning



This is a hands-on machine learning project where I tried to answer a interesting question: Can we use historical stock data for Reliance Industries to reasonably predict tomorrows closing price for Reliance Industries?



I used 5 years of data for Reliance Industries and built a regression model using technical indicators like moving averages, RSI, volatility and momentum for Reliance Industries.



The result is really good. I got 95% R² on test data for Reliance Industries. And when I made a prediction for Reliance Industries I was only off by 1.08%. That is just ₹15 off on a ₹1416 stock for Reliance Industries.



This is not magic. It does not mean I can beat the market for Reliance Industries. It is solid modeling and evaluation for Reliance Industries.



Why I Built This



Stock prices for Reliance Industries look random at first.. When you start breaking them down into trends, momentum and volatility for Reliance Industries you start to see patterns.



I did not just want to learn about machine learning theory. I wanted to use it for something something that connects finance and machine learning for stock price prediction.



This project helped me understand how financial data for Reliance Industries behaves. It also helped me learn about time-series modeling and how it's different from normal machine learning problems for stock price prediction.. I found out that sometimes simpler models can outperform complex ones, for Reliance Industries stock price prediction.



What I Did



I did not use the raw prices in the model. Instead I made some features that are more useful.



These features are:



\* Moving Averages for the 10, 20 and 50 days to see which way the trend is going



\* RSI to see if the stock is too expensive or too cheap



\* Volatility to see how risky it is I used the deviation for the last 30 days



\* Momentum to see how strong the movement is I used the change over the last 10 days



Then I trained two models:



1\. Linear Regression



2\. Random Forest



It was surprising that Linear Regression worked better.



The Random Forest model was very good at training but not good at testing it overfit.



I learned a lesson:



Just because something is complicated it does not mean it is better.



Results



I used data from 2019 to 2023 to train the model.



I used data from 2023 to 2024 to test the model.



The test score was 0.9518.



The real error was 1.08%.



I made sure to do some things:



\* I split the data based on time I did not shuffle it



\* I scaled the features properly



\* I compared the models I did not just trust one



What This Project Really Shows



This project is not about me saying I can predict the markets perfectly.



It shows that I can do some things:



\* Collect and clean financial data



\* Make features that are useful



\* Use machine learning properly for time series problems



\* Find overfitting



\* Evaluate models honestly



That is the real value of this project.



Tech Stack



I used Python.



I used yfinance and other libraries, like pandas, numpy and scikit-learn.



I also used matplotlib.



If I improve this project I would try some things:



\* I would try using LSTM models



\* I would use walk-forward validation



\* I would predict returns of raw prices



\* I would test a trading strategy of just measuring the score

