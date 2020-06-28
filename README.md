
# Module 2 Final Project


## Introduction

This project is dedicated to developing a model that best predicts house prices in King County, Washington.
The descriptions below are a high level overview of each notebook and how each notebook contributes to the final model
that predicts house prices in King County. The general approach was to create a model that best predicts house prices for 
an "average" household with homes greater than $800,000 not included in the modeling. 


## Notebooks

### KC Data Cleaning

This notebook as the name suggests focuses on first a high level overview of the data set and then a dive into more technical
scrubbing of the data. This notebook handles missing values in multiple ways, data types, outliers, and categorical variables.

### KC EDA and Data Manipulation 

The EDA notebook applies data visualization to help explore the data and its structure. Statistical assumptions are also addressed
and where possible corrections to the data are made e.g. removal of highly correlated variables. Transformation of the data is also
accomplished in various ways such as through log transformation and scaling in order to prepare the data to perform better during 
the modeling phase. 

### KC Maps

This notebook contains a brief exploration of the geospatial data contained within this data set using the Folium library. 
Various maps were created using Folium to explore variables such as how income relates to zipcode and waterfront property prices.

#### KC Model 

This notebook focuses on the modeling phase of the project. Contained in this notebook are the steps taken to model the data using
multi variable regression. Key features are discusssed and their impact on house prices in King County, Washington. 
