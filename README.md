# Intro-to-Linux-and-Shell-Scripting

## Lab 1 
#### Create a bash script to extract weather data

- create an automated Extract, Transform, Load (ETL) process to extract daily weather forecast and observed
  weather data and load it into a live report to be used for further analysis by the analytics team.
- use the weather data package provided by the open source project wttr.in, a web service that provides weather  
  forecast information in a simple and text-based format.
- use the curl command to scrape weather data via the wttr.in website.
- ETL script: [weather_script](ETL_Weather.sh)

#### Create a script to report historical forecasting accuracy
- create script to measure and report the accuracy of the forecasted temperatures against the actuals.
- forecast accuracy script: [forecast accuracy script](forecast_accuracy.sh)

## Course Project

- creating a script called backup.sh which runs
  every day and automatically backs up any encrypted password files that have been updated in the past 24 hours.
- backupscript: [backup.sh](https://github.com/Aminsfwt/Intro-to-Linux-and-Shell-Scripting/blob/main/backup.sh)
