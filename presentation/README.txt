Link to video of presentation:
https://vimeo.com/316166610

In this video, I present my findings for the research I conducted on the correlation between sentiment values of a stock and the daily returns/losses and developed an LSTM network to forecast closing prices at UCI's Data Analytics Bootcamp for my final project.
My goal was to develop an alpha model (which simply put tries to predict/use some information to make money from stocks) that would trade on a daily basis. Along the way, I found that the movement between sentiment scores and daily returns do not always make sense and that there is not a steady stream of data that can be used for my purpose.
I read through several articles to guide research over the topic and found one where the author compared several ML/statistical models and their effectiveness in predicting stock prices, where he concluded that the most effective out of his bunch was a LSTM network.
In my research, I attempted to test his findings and found that the effectiveness for predicting sequential data, such as stock prices (where the trends do not follow any sort of seasonality or general pattern), was very effective.