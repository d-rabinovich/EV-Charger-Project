# EV-Charger-Project

Semester-long Machine Learning project selecting features to predict the use of Electric Vehicle (EV) chargers in Los Angeles and implementing Cost-Effective Lazy Forward (CELF) selection to optimally place new chargers. 

## Abstract

The City of Los Angeles has set goals to increase the percentage of zero-emission vehicles in the city-wide fleet to 25% by 2025 and 100% by 2050. To advance this goal, the City plans to install 150 new electric vehicle (EV) charging stations in 2021. This project utilizes census data, Google and Bing Map applications, and data published by the state of California in a linear regression model to determine which features of current EV charging stations and the neighborhoods that they are in most accurately predict the usage patterns for a particular station. Subsequently, we will apply our understanding of those predictive characteristics to a greedy max cover algorithm such as CELF to determine the optimal placement of new EV charging stations to maximize results including total power delivered, total charging time, and the number of charging sessions. 


The scripts are organized as follows:

## data_cleanup

This file contains cleanup and preprocessing for our three data sources: 

1. Vehicle Fuel Type Count by Zipcode published by California Open Data
2. Census Data taken from the American Community Survey (ACS) five-year estimates
3. Usage statistics for 173 of the EV Chargers in Los Angeles County between May 1st, 2019 and June 12th, 2020

### Vehicle Fuel Type Dataset

### Census Data

### Charger Usage

## circular_geoanalysis

## regression

## pipeline

## celf_set_cover_final
