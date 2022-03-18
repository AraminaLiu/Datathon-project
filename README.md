# Datathon-project
Problem Description:

National Data Buoy Center (https://www.ndbc.noaa.gov/) stores meteorological data from various stations in the oceans. These stations are in strategic locations close to offshore oil and gas platforms and the data obtained from these stations are extremely important to understand the various conditions an offshore platform experiences. In this challenge you will build an interactive dashboard where you will enter the name of the station and will be able to retrieve the wind speed and wind direction at that station for the past 45 days.

Objective:

Using a combination of tools of your choice you will build an interactive dashboard where upon entering the platform name you will be able to visualize the wind speed and wind direction in a time series plot. You will also forecast how wind speed and direction will change in the next 72 hours. In addition to the time series plot your dashboard should also show a polar plot of the daily average wind speed in the mean direction of that day. You should be able to select the day interactively for the daily polar plot. 

Data sources:

Real time (past 45 days) standard meteorological data for three stations and data description:

1.	KIKT station
https://www.ndbc.noaa.gov/data/realtime2/KIKT.txt
https://www.ndbc.noaa.gov/measdes.shtml#stdmet

2.	KAPT station 
https://www.ndbc.noaa.gov/data/realtime2/KBQX.txt
https://www.ndbc.noaa.gov/measdes.shtml#stdmet

3.	KMIS station
https://www.ndbc.noaa.gov/data/realtime2/KMIS.txt
https://www.ndbc.noaa.gov/measdes.shtml#stdmet

If any of the links above do not work use the following stations:
a.	https://www.ndbc.noaa.gov/data/realtime2/PCNT2.txt
b.	https://www.ndbc.noaa.gov/data/realtime2/VCAT2.txt
c.	https://www.ndbc.noaa.gov/data/realtime2/FMOA1.txt


Non-Monetary Prizes:
Each member of the winning team will get a $100 Amazon gift card.
Additional Resources:
●	You can add more platforms from https://www.ndbc.noaa.gov/
●	Extra credits for teams that will be accessing the data directly from the web instead of downloading and storing them locally
●	You can use dashboarding tools like streamlit, plotly, jupyterlab
●	If the data is not available display appropriate messages
