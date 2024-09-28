# Project Description
This project is for CSCA 5632 at CU Boulder. 

## Deliverable 1 
A Jupyter notebook showing an unsupervised learning problem description, EDA procedure, analysis (model building and training), result, and discussion/conclusion. 

**Please see Final_Notebook.ipynb**

## Deliverable 2
A video presentation or demo of your work. The presentation should be a condensed version as if you're doing a short pitch to advertise your work, so please focus on the highlights:

What problem do you solve?

What ML approach do you use, or what methods does your app use?

Show the result or run an app demo.

The minimum video length is 5 min, the maximum length is 15 min. The recommended length is about 10 min. Submit the video in .mp4 format.

**Please see presentation.mp4**

## Deliverable 3 
A public project GitHub repository with your work (please also include the GitHub repo URL in your notebook/report and slides).

**Please see this comment you're reading right now. Hello!**

## Details
In the last project (supervised learning / linear regression analyzing factors for net immigration loss v gain) we collected a few datasets on countries GDP per Capita, Population, Net Immigration Levels, and compare them to some popular indices that attempt to measure levels of conflict, danger, or social progress. Our indices will be Global Peace Index (GPI), ACLED Conflict Scores, and Social Progress Score. We analyzed net immigration inflow vs outflow of various countries and compare them to these indices, focusing on what factors influence net inflow or outflow.

For this project we will be using the same datasets, but we will be using unsupervised learning to analyze the data. We will be using K-means clustering to analyze the data and compare the results to the supervised learning project. 

### Motivations
Can we observe any interesting clusers among the countries? 

### About the Data
GPI data is from https://worldpopulationreview.com/country-rankings/most-dangerous-countries
"The GPI report evaluates 163 countries that account for more than 99.7% of the world’s total population. The factors analyzed in the report are grouped into three different areas: Safety and Security, Ongoing Conflict, and Militarization. The factors used to compile this report include: the number of internal and external violent conflicts, level of distrust, political instability, potential for terrorist acts, number of homicides, and military expenditures as a percentage of GDP. A score is calculated for each of the 163 nations featured in the report based on these factors. The higher the score, the more dangerous the country is and the lower it ranks in terms of safety."

Conflict Index is from https://acleddata.com/conflict-index/
"The ACLED Conflict Index assesses every country and territory in the world according to four indicators – deadliness, danger to civilians, geographic diffusion, and armed group fragmentation – based on analysis of political violence event data collected for the past year. The top 50 ranked countries and territories are experiencing extreme, high, or turbulent levels of conflict."