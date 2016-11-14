# NOAA-GET-Weather-Data
Implementation of RESTful GET requests to download daily weather data from NOAA from 2010/01/01 to 2015/12/31

# NOAA
NOAA provides weather data using RESTful web services available here: http://www.ncdc.noaa.gov/cdo-web/webservices/v2#gettingStarted

# Python Code
NYC_Weather_Data.ipynb is the IPython Notebook that shows code for contacting REST API to download historical daily weather data from NOAA website

# Information needed to download
NYC_NOAA_Details.txt provides station name and ID needed to pass to GET request header to specify location of interest

# Results
Result is available as a .csv file (PreProcessed_Weather_Data_20100101_20151231.csv) in cleaned format. 
