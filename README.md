# Propel_Crime_Data
This is our Propel Data Repository 
# This is our code
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
