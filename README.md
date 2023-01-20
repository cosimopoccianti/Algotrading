# Algotrading
Academic project to predict trends in financial time series.

*Authors*: [Cosimo Poccianti](https://github.com/cosimopoccianti), [Miro Confalone](https://github.com/mirocon), [Hanna Carucci Viterbi](https://github.com/hannacarucci), [Lorenzo Antolini](https://github.com/loreIT)

<img src="logo/python_logo.png" height="30" />


The project, carried out in cooperation with the Euklid fund, which defined the baselines and objectives, aims to predict whether the stock market will go up or down, based on the time series of the closing prices of single indices and appropriately calculated financial oscillators, such as moving averages or RSI.

The time series analysed cover roughly the last 20 years. The financial indices are WTI, GOLD, NASDAQ and IBM, the datasets come partly from the Euklid fund and partly from Yahoo Finance. The data are processed with some simpler algorithms, such as a logistic regression or a K-Means clustering, and some more complex ones such as a Deep Neural Network or an Extreme Learning Machine. The various outputs of the algorithms are then put together in an ensemble model, represented by a Random Forest. Finally, an LSTM model was also made. More precise indications can be found in our [presentation](project_presentation.pdf) and [report](project_report.pdf). 