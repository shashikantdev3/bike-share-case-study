# Bike Share Case Study

* To see the detailed reports of Analysis on website : [Click Here](https://imshashikantdev.github.io/bike-share-case-study/)
* To see the detailed reports of Analysis on Kaggle : [Click Here](https://www.kaggle.com/shashikantdev/case-study-cyclistic-bike-share)


![Cyclistic Company Logo](logo.png)

# Background

This analysis is for case study 1 from the Google Data Analytics Certificate (Cyclistic). It’s originally based on the case study “‘Sophisticated, Clear, and Polished’: Divvy and Data Visualization” written by Kevin Hartman [click here]( https://artscience.blog/home/divvy-dataviz-case-study>) to visit the original blog post. We will be using the Divvy dataset for the case study. 


## Purpose

The purpose of this script is to consolidate downloaded Divvy data into a single data frame and then conduct simple exploratory data analysis to help answer the key question: *“In what ways do members and casual riders use Divvy bikes differently?”*

## Business Task

To analyze user behaviors on how annual members and casual riders use Cyclistic bikes differently to make recommendations on how to convert casual riders into annual members

### Information about the dataset

Regarding the dataset, we have the following information:

  * It is external data stored in the [cloud](https://divvy-tripdata.s3.amazonaws.com/index.html)
  * It used the long data format
  * First-party data (reliable and original)
  * There is a file for each past 12 months (current)
  * It is distributed under a [license](https://www.divvybikes.com/data-license-agreement)
  * There is not Personally Identifiable Information (PII)
  
  
### Data acquisition process
The following process is utilized:

  * Each dataset is downloaded
  * Appropriately stored in a folder for original datasets
  
### Identifying 

To identify issues with the data, we:

  * Evaluate the ride length and spot unusual observations
  * Filtered the data and identified missing values
  * Sorted the data and found inconsistent attribute format


### **Process**
Here, we will perform the data cleaning, ensure integrity, and that it is complete,
correct, and relevant.

### Tools
We selected tools to perform specific tools, as described next.

  * R: develop scripts to clean, transform, organize, and summarize the datasets
  * Tableau: create data visualizations
  * R Notebook: provide a complete report of the data analysis process


## Install Required Packages

* tidyverse for data import and wrangling
* libridate for date functions
* ggplot for visualization

