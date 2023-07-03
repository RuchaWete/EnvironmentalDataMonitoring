link to get Data to run AirPollutionClimateParameters.ipynb notebook 
https://drive.google.com/file/d/1X5Zv2RddODHMelIaC6EB4KlhI3CGGbey/view?usp=sharing

link to get Data to run WaterPollution.ipynb notebook 
https://drive.google.com/file/d/1nyyPkymQ-ZJAQZdqdLoG6Pl5Bc3zftmf/view?usp=sharing

# EnvironmentalDataMonitoring
AI system that can collect, process, and analyze various types of environmental data. The system provides insights and visualizations to understand the current state of the environment.

# Air pollution notebook
The airpollution jupyter notebook has been trained on the dataset available in the google drive link above. This file achieves the following: -
1. Merging and cleaning the data, dealing with null values and formatting the data. Repetetive columns were reomved. The following are the final colums - 


![WhatsApp Image 2023-07-03 at 22 42 17](https://github.com/RuchaWete/EnvironmentalDataMonitoring/assets/77842772/f7d118c1-ef6d-4bd7-89f6-a5d36dfe042b)

Dataset after cleaning is - 

![WhatsApp Image 2023-07-03 at 22 42 58](https://github.com/RuchaWete/EnvironmentalDataMonitoring/assets/77842772/4f08fa18-4470-44fe-a934-e036e79ecb7f)

2. Heatmap is used to plot null values column-wise

![WhatsApp Image 2023-07-03 at 22 49 55](https://github.com/RuchaWete/EnvironmentalDataMonitoring/assets/77842772/5f2728bd-58db-4adc-a0e4-afde8591cef9)

3. Different methods were used to predict null values. ALl the results were plotted and the closest approximation was used. Hence, linear approximation was used to fill null values. 
4. Correlation was calculated using eatmap. We checked for multi-colinearity. There was no multicolinearity as highest correlation value was 0.86
5. Performed time series analysis for each metric and created a point plot for it. Variance over year gaps was plotted.
6. Line plot for different pollutants was plotted. Some pollutants have not changed over time while some have changed considerably. The total level of pollutants has fallen over time.
7. Regression plots were plotted among the different variable to infer different correlations. These were the correlations we inferred - 

![WhatsApp Image 2023-07-03 at 22 49 58](https://github.com/RuchaWete/EnvironmentalDataMonitoring/assets/77842772/7a83a496-ee61-41fe-bd61-41f41b8ef0ba)

8. Linear regression was trained on inferred correlations. The regressions have very satisfactory values which have been attached below - 

![WhatsApp Image 2023-07-03 at 22 54 03](https://github.com/RuchaWete/EnvironmentalDataMonitoring/assets/77842772/d6b65864-fc1d-42c9-8ed5-3e99cd489f04)
We can clearly observe that the p-values are very low making the regression accurate. We can further infer the coefficients to understand the impact of different gases on air pollution.

To successfully run the notebook file ensure the path has been set correctly.


# Current Data Visualization
Current data was obtained from weather websites and output to the csv file statewise. This was then visualized using Power BI. The dashboard "Airpresent" has graphs representing this data in an easy to understand and coherent manner. The datafile can be updated with more recent data to automatically update the visuals.



