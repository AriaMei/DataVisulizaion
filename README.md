#####
####Environment:
#####

os
pandas
matplotlib
scipy
numpy
dash
dash_core_components
dash_html_components
dash.dependencies
plotly
sklearn
torch
seaborn
sklearn

#####
###################################

How to Run the project:
#####

Run the 'MacauWether.ipynb' file cell by cell


####
######################################

######################################

dataset
####
Macau_weather_dataset.csv

This is an annual weather data provided by the government of Macao China from 1999 to 2019, It contains 7,537 pieces of data. “Date”, “Mean maximum (ºC)”, “Mean(ºC) ”, “Mean minimum (ºC)”, “Mean
relative humidity (%)”, “Insolation duration(hour)”, ‘ Total rainfall (mm) ’ 7
dimensions, the original data is a total of xlsx format table, in order to facilitate
the data processing, the data was converted into a csv file. In the rain fall data,
there is “VST” indicating rainfall below 0.2, and “VST” has been replaced with
0.1 for ease of calculation

###################################
###################################

file description

log: store the .pth file of training model 

images:tore the image of report
