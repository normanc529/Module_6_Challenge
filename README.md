## Module_6_Challenge

This module challenge is for Houseing Rental Analysis for San Francisco and the surrounding neighborhoods

required libraries and dependencies:

import os
import pandas as pd
import plotly.express as px
import hvplot.pandas
from pathlib import Path
from dotenv import load_dotenv

using mapbox API, we pull data to chart our findings in the csv files that we have which are:
housing peryear
neighborhood coordinates
census data for sf neighborhoods

we first calculate data points such as housing units per year, price per sq ft, gross rent, etc to plot and compare the differences or correlations between the data points

Taking data from 2010 to 2016, we also calculate the trend between the averages of the data points

after that, we plot the information with the mapbox API to visualize the most concentrated areas of price to value/living space

![Screenshot 2021-02-14 025217](https://user-images.githubusercontent.com/75395061/107874636-b0b4db80-6e6f-11eb-89e4-f9265a60b01d.png)
