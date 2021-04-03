# Tracking Progress of Covid-19 Vaccination Program Worldwide

## Introduction
People around the world are waiting for resuming to their normal life since the pamdemic (Covid-19) started in early 2020. One of the best ways that people could have a normal life is vaccine. Many countries starts provide a covid-19 vaccine for many people. This code is to provide data analytics to see how progress we are about Covid-19 vaccination program around the world.

The data is originally from [Our World Data](https://ourworldindata.org/). However, it has been done the pre-processing data and is provided in csv format by Gabriel Preda on [Kaggle](https://www.kaggle.com/gpreda/covid-world-vaccination-progress/). This code will process this data and visualise to find data insight.

This code is developed in Python (3.7.6) and uses some frameworks related to data analytics.
* Pandas (1.2.1) : to do data processing
* matplotlib (3.1.3) : to visualise data
* geopandas (0.9.0): to visualise data in world map

## Business Understanding
We would like to track the progress of Covid-19 vaccination program around the world with having 3 questions.
* What are countries having the highest progress rate in building heard immunity by vaccine?
* What are the counties providing the highest number of vaccine to their people per day?
* What has vaccine been used the most in many countries?

## Data Understanding
The data is in .csv format. It contains the data about progress in vaccination in 162 countries. The latest data in on 2nd of April 2021. The data shows raw data about numbers of people are vaccinated, by date, by country. These are some examples of the data.
* Country
* Date
* Number of vaccinations per day
* Total number of people fully vaccinated per hundred
* Vaccines used in the country

## Data Preparation
The data is processed in different ways depending on what business question we try to answer. However, they are following the same processes.
* (1) Clean data
* (2) Transform the data into a format for visualisation (data processing)
* (3) Visulise data

## Analysing Data
Once the data is completely processed into graphs. We can see the data insight. Here is a full report of this data [LINK](https://nontawat149.medium.com/tracking-progress-of-covid-19-vaccination-program-worldwide-d973951b2517). 

