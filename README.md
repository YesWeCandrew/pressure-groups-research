# Professionalisation trends in modern Australia

This repository contains my research for the ANU Pressure Groups and Political Lobbying course. I received a High Distinction for my work and was asked to share my code and research with the course convenor, Professor Darren Halpin. My research focused on professionalisation trends within Australian civil and interest groups. 

## Data wrangling

To investigate, these trends I used the Australian Charities and Not-for-profits Commission's annual Charity Register data. I combined seven years of this data sets to view trends within organisations during this time. 

To identify which charities in this dataset were civil and interest groups, I initially used a list of names of such groups provided in previous research. I used the Australian Governments ABN Lookup API to retrieve each group's business number which could then be used as a primary key to identify the group in the dataset. This was later replaced with a list of the organisations business numbers provided by Professor Halpin. This was more accurate, as some groups business names were not similar to their trading names, preventing the API from finding an accurate match.

## Data analysis

Once the civil and interest groups had been identified and the data sets cleaned, I conducted analysis on the groups to attempt to identify trends of increase staff head counts and decreases in volunteer numbers. I used the Mann Kendall test to determine whether there were statistically significant increases in either of these factors over time. I used Seaborn to visualise the results in Python.

## View files

You can see all my code and results in the [Data wrangling and analysis](/Data%20wrangling%20and%20analysis.ipynb) Jupyter Notebook. 

The raw data files are available in the [data branch](https://github.com/YesWeCandrew/pressure-groups-research/tree/data).

## Copyright

Copyright © 2023, [Andrew Howes](https://github.com/YesWeCandrew)