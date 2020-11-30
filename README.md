# PREDICTION-ARIMA

**ARIMA**, short for ‘AutoRegressive Integrated Moving Average’, is a forecasting algorithm based on the idea that the information in the past values of the time series 
can alone be used to predict the future values.
Any ‘non-seasonal’ time series that exhibits patterns and is not a random white noise can be modeled with ARIMA models.

We make a ARIMA forecast of the avocado prices in Spain.


## Pre requirements 📋


For this project, we need the following python libraries:
  Pandas, Numpy, Statsmodelapi, matplotlib, pmdarima, datetime

And I use the data "C:/Users/manut/Downloads/AGUAC.csv"

## Install Libraries 🔧

import pandas as pd
from matplotlib import pyplot as plt
import numpy as np
import statsmodels.api as sm
from statsmodels.tsa.stattools import adfuller
from statsmodels.tsa.stattools import acf
from statsmodels.graphics.tsaplots import plot_acf
from statsmodels.graphics.tsaplots import plot_pacf
from statsmodels.tsa.seasonal import seasonal_decompose
from statsmodels.tsa.arima_model import ARIMA
import pmdarima as pm
from pmdarima.model_selection import train_test_split
from pmdarima import auto_arima
from pandas.plotting import register_matplotlib_converters
register_matplotlib_converters()
from datetime import datetime



