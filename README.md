# Sentiment Trading Strategy/Simulation

**Scope**: The goal of our project is to compare sentiment-based trading strategies with traditional simple moving average (SMA) trading strategy. Our analysis will include the application of machine learning models to historical data obtained from Google search trends, the Fear and Greed Index from  alternative.me, and price from Alpaca API. The data analysis and visualization will be created in a Jupyter notebok with Pandas.

## Methods

### Data sources

***Sentiment Metrics:***

- [Google (search trends)](https://trends.google.com/trends/explore)
- [Alternative.me](https://alternative.me/crypto/fear-and-greed-index/#history) (Fear and Greed Index)

***Value Metrics:***

- [Alpaca API](https://alpaca.markets/) (price and SMA)

***Analysis:***

- [Jupyter](https://jupyter.org/) notebook, 
- [Pandas](https://pandas.pydata.org/docs/) (historical data)

***Confounding Factors:***

- Time/window of available data

***Outcomes:***

- Comparison of historical data performance

- Application of where a portfolio would be in a given historical time frame (past to present)

- Machine learning model to predict where a portfolio would be at the end of the year (forecasting)


**Additional Technical Requirements:**

- *at least* 1 machine learning model, libary, or metric **that we have not done in class**

	<h6>- fit the model</h6>
	<h6>- get metrics, visualizations</h6>
	<h6>- use predictors</h6>


## Installations

```
conda update -n base -c defaults conda

conda activate base
conda create -n sentenv python=3.7 anaconda -y
conda activate sentenv
conda install -c conda-forge imbalanced-learn -y
conda install python-graphviz -y
conda install graphviz -y
conda install -c conda-forge pydotplus -y
conda install -c conda-forge pytrends
pip install jupyterlab_sublime
pip install fastquant

```