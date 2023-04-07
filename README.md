# DATA 3320 (project 1: rain in Seattle and St. Louis)
## Purpose 
The purpose of this assignment is to create a GithubLinks to an external site. repository that will allow you to organize and share your project materials.
By performing this work you will learn:
1. How to create a Github repository
2. How to add data to a Github repository

the second purpose of this project is to produce a weather data set that is prepared for the analysis steps of the data science methodology to answer the question of whether it rains more in Seattle, WA than in St. Louis, MO. 
<br/>By performing this work you will learn:
1. How to perform data cleaning
2. How to write a well-organized and well-commented Colab notebook
3. How to export a data set from Python

## Overview
this project is to look at two data sets and determine which location has more rain

## Data
[seattle_rain.csv](https://raw.githubusercontent.com/longhtt/Seattle-Weather/main/seattle_rain.csv)
shows daily precipitation from one station in the Seattle area

[stl_rain.csv](https://raw.githubusercontent.com/longhtt/Seattle-Weather/main/stl_rain.csv)
shows daily precipitation from multiple stations in the St. Louis area

note: seattle_rain.csv and stl_rain.csv are copied from [here](https://github.com/brian-fischer/DATA-3320/tree/main/weather) 

seattle_rain.csv and stl_rain.csv both sourced from [NOAA Climate](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND).

## Data Preparation

[Long_Tran_Thien_DATA_3320_Seattle_St_Louis_Data_Preparation.ipynb](https://github.com/longhtt/Seattle-Weather/blob/main/Long_Tran_Thien_DATA_3320_Seattle_St_Louis_Data_Preparation.ipynb) a Colab Notebook that shows how [clean_seattle_stl_weather.csv](https://raw.githubusercontent.com/longhtt/Seattle-Weather/main/clean_seattle_stl_weather.csv) was prepared.

# short summery of steps taken

1. Import libaries
2. Load data
3. explore contents of data sets 
4. convert data types
5. Selecting relecant subsets of data
6. join data frames
7. creating a tidy data frome
8. create relevant derived variables 
9. identify and dealing with missing values
10. exporting clean_seattle_stl_weather.csv
11. plots
