# hotel-data-analysis
## Part 1: Descriptive Analysis 

●	Gave  a pivot view summary and suitable visualization for the following:
o	 The total number of visitors segmented by each level, every month in each year
o	The percentage difference in the number of visitors between different regions and years 
o	Looked out for outliers and handled them. Used visualization to showcase outliers before and after treating them. 

## Part 2: Prescriptive Analysis 
●	Analyzed the data for the region performing worst in all the years and prescribed what could be the reason and how to improve the number of visitors from that region.
●	Based on the given data, identified which region is having a better YearOnYear growth.
o	Created a new feature (Level 5 visitors/Level 1 visitors) and found what were the top 3 states based on that created feature for all the available segments and each given year. 
o	Created another metric apart from (Level5 visitors/Level1 visitors) and performed the same task as above. Compared if the states are same in both the questions and created a hypothesis about the reason behind it.

 ## Part 3: Prediction 
Wrote a function called predict_future(‘Region’,’Segment’) which, when called, would perform the following activity:
o	Predicts the “Level 5” future values for the next 6 months, given the parameters of the function. (Made sure the parameters have default values in place) Also, plotted it.
o	Generated the MAPE and RMSE of my prediction of the year 2022, 2021 & 2020 for the given parameters.
Plotted a line graph of the level 5 actual numbers from 2020-2022 & in the same graph, there gave the predicted numbers for 2023. The x-axis was the timeline from 2020 Jan to 2023 Jun and the y-axis was the value of the level 5 column and predicted values. 

## Part 4: A/B testing 
Used  “AB_TEST” sheet in that excel file, and created few possible metrics for A/B testing 
Performed an AB testing to find which variation (whether control or treatment) is better.

