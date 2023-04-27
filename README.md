# READ ME

This repository is designed for the 1.00 - Engineering Computation and Data Science - Final Project. For this project, we explore a dataset provided by the City of Cambridge that reports crimes within the city dating back over the past decade. We analyze trends, plot the data on a map, and try to predict different aspects of crime within Cambridge.

The "explore.ipynb" walks through basic exploration of the data. This includes histograms of crime types, pie charts of crime by neighborhood, and more. We use 80,000 records from the dataset for this exploration. A new user can already view the results within the jupyter notebook or can choose to run the code themself. 

The "mapping.ipynb" maps the data points of crimes that occurred to a map of the city of Cambridge. As is, the file only imports the first 8,000 records of crime due to time considerations of running the code. If a user desires to use more or less records for the map, simply change the limit at the end of the URL in the beginning of that file. After importing the data, the data points are prepped and converted to longtitude and latitude coordinates. The data points are then plotted on a map. A user can view the outputs of the jupyter notebook or run it themself.

".mapbox_token" contains the API key associated with a Mapbox account. This key is called in the "mapping.ipynb" file to allow the file to access the map for plotting. This file should not be altered unless the user posesses a different key to use. 

Python and Copilot extensions are included in the devcontainer. All required libraries are included in the requirements.txt and will automatically install upon build. 