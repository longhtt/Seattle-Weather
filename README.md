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

And the last purpose of this projext is to perform work using the data science methodology to answer the question of whether it rains more in Seattle, WA than in St. Louis, MO. <br/>
By performing this work you will learn:

1. How to use the data science methodology to answer a question
2. How to write a well-organized and well-commented Colab notebook
3. How to share your work to support reproducible research


## Description 
this project is to look at two data sets and determine which location has more rain, Seattle or St. Louis <br/>
with both cities being given tables to show their daily precipitation, we will answer the question: <br/>
which city has more rain?
### Conclusion
After preparing and fixing the data for analysis we are able to make a general conclusion that St. Louis rains more than Seattle during Summer while Seattle rains more then St. Louis during winter, but St. Louis rains more overall in a yaer than Seattle

## Requirements 
must require a GitHub account and access to Colab that runs the Data Preparation and Data Analysis 

## Data
[seattle_rain.csv](https://raw.githubusercontent.com/longhtt/Seattle-Weather/main/seattle_rain.csv)
shows daily precipitation and other information from one station in the Seattle area

[stl_rain.csv](https://raw.githubusercontent.com/longhtt/Seattle-Weather/main/stl_rain.csv)
shows daily precipitation and other information from multiple stations in the St. Louis area

both seattle_rain.csv and stl_rain.csv are copied from [here](https://github.com/brian-fischer/DATA-3320/tree/main/weather) <br/>
but originally sourced from [NOAA Climate](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND).

## Data Preparation

[Long_Tran_Thien_DATA_3320_Seattle_St_Louis_Data_Preparation.ipynb](https://github.com/longhtt/Seattle-Weather/blob/main/Long_Tran_Thien_DATA_3320_Seattle_St_Louis_Data_Preparation.ipynb) a Colab Notebook that shows how [clean_seattle_stl_weather.csv](https://raw.githubusercontent.com/longhtt/Seattle-Weather/main/clean_seattle_stl_weather.csv) was prepared.

[clean_seattle_stl_weather.csv](https://raw.githubusercontent.com/longhtt/Seattle-Weather/main/clean_seattle_stl_weather.csv) shows only the the daily precipitation from one station of both Seattle and St. Louis in a single file based off data from seattle_rain.csv and stl_rain.csv

### short summery of steps taken to prep clean_seattle_stl_weather.csv
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

## Data Analysis 
Using the clean data file created from the data preperation, and create a notebook for analysis [Long_Tran_Thien_DATA_3320_Seattle_St_Louis_Analysis.ipynb](https://github.com/longhtt/Seattle-Weather/blob/main/Long_Tran_Thien_DATA_3320_Seattle_St_Louis_Analysis.ipynb)

### short summery of steps taken to make analysis
1. Import libraries
2. Load clean data
3. Stating questions
4. Analysis
5. Results for communication assignment
6. Conclusion

## Authors
Creator of repository: Long Tran-Thien

## License  
Anyone may reuse material from this repository but must credit me 'Long Tran-Thien'

