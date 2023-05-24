# Propel_Crime_Data
This is our Propel Data Repository 
# This is our code for importing and installing Packages
install.packages("usethis")
install.packages("learnr")
install.packages("readr")
install.packages("devtools")
install.packages("tidyverse")
library(usethis)
library(learnr)
library(devtools)
read.csv("\\Users\\groovy's\\Desktop\\Crimedata_Rstudio\\Crime_Data_from_2020_to_Present.csv")
g <- read.table("C:\\Users\\groovy's\\Desktop\\Crimedata_Rstudio\\Crime_Data_from_2020_to_Present.csv" , fill= TRUE, header = T, sep= ',' )
# Describing our dataset
We are interested in seeing the # of specific crime rates in Los Angeles. In this dataset, we focus on analyzing the average count of specific crimes commited in Los Angeles from 2020 to 2023 (present time). 
# Questions of interest
On average, how often does theft occur in Los Angeles from 2020 to Present?
On average, how often does burglary occur in Los Angeles from 2020 to Present?
# Resource:
https://catalog.data.gov/dataset/crime-data-from-2020-to-present
# Video Link:

