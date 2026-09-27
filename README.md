# CS 506 Final Project
**Doyoung Kim, Coltrane Margosian, Zohaib Mohammad, Yewon Yun**
---
## Description & Goal
  The project's goal is to seek a model that can predict what percentage of housing units (e.g. apartments, houses) are vacant based on the minimum wage, per state. If this goal is too ambitious, we can focus on just Massachusetts. If the goal is too unambitious, we can analyze which states resemble each other in their data and attempt to tie such resemblances to other state data such as demographics. Within our project, we will additionally need to consider municipalities and counties with higher minimum wages than their state, though our exact method of practically doing so is yet to be known.
## Methodology
  To obtain the data needed for the project we have found CSV and Excel spreadsheets for both the gross vacancy rates and the minimum wage for every state in the United States from 2005 up until 2025. Using these files, which we will collect simply by downloading them and placing them in spreadsheets, we will plot our data and use clustering to explore the relationship between the minimum wage and home vacancy.
### Sources
* Minimum wage by state over time: https://fred.stlouisfed.org/release?rid=387
* Vacant housing per state: https://www.census.gov/housing/hvs/data/prevann.html 
* Property values by county: https://www.fhfa.gov/data/hpi/datasets?tab=hpi-datasets 
* Municipalities/counties with higher minimum wages than their state: https://www.epi.org/minimum-wage-tracker/
## Timeline
### October
#### Week 1-2: 
* Download data sources for minimum wage over the years and rental vacancy by state
* Convert to csv and clean up the dataset using pandas
* Find additional sources available for potential factors such as unemployment, demographic, political alignment
#### Week 3-4: 
* Combine datasets into a table and calculate minimum wage change rates and vacancy rate
* Plot trends over time and note any unusual patterns
* Create initial visualizations via matplotlib
* October mid-project check in
### November
#### Week 1-2:
* Create more visualizations for statistically significant correlations
* Write a brief summary of data processing, modeling methods, and results
* Train and evaluate a model to predict changes in rental vacancy based on minimum wage changes and other appropriate factors
#### Week 3-4:
* Create a visualization of the model’s prediction and accuracy
* November mid-project check in
### December
#### Week 1:
* Write a final report including data visualizations
* Create, record, and submit presentation describing data modelling, processing, and results by 12/9
