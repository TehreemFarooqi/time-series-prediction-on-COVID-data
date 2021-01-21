# Prediction of spread of COVID-19 in Pakistan based on countries with similar previous spread
LSTM is the best model for time-series prediciton and that's why it is implemented for the data using `torch`, `Numpy` and `scikit-learn`. COVID spread data in different countries until 27th May, 2020 as taken from Kaggle (https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) is preprocessed to find the countries with trend most similar to Pakistan using Correlation. Using these countries and Pakistan data, different timelines are predicted from 27th May, 2020 to 27th June, 2020. Timelines from 10th May to 27th May are plotted against the actual data of each country for comparison. At the end, you can also see a plot showing all timelines.

These predicted timelines were doing fine until the second wave :( Stay safe guys!

*Tools and Technologies used: Python, Numpy, Scikit Learn, Torch, matplotlib, seaborn, pandas*
