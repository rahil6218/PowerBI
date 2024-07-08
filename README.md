# PowerBI Dashboard for accident analysis 
## Overview

This Power BI Dashboard provides an in-depth analysis of road accidents, comparing data from 2021 and 2022. The dashboard visualizes various aspects of road accidents, including accident types, road conditions, weather conditions, types of injuries, and number of deaths. The goal is to identify patterns and insights that can help in understanding and mitigating road accidents.

## Tools
Microsoft PowerBI [DOWNLOAD](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

## Features

- Comparison of Road Accidents (2021-2022): Analyze and compare the number of road accidents between the years 2021 and 2022.
- Type of Road: Examine how different types of roads influence the occurrence of accidents.
- Road Condition: Visualize the impact of road conditions on accident rates.
- Weather Condition: Analyze the role of weather conditions in road accidents.
- Types of Injuries: Break down the injuries into categories such as slight, serious, and fatal.
- Number of Deaths: Display the total number of deaths resulting from road accidents.

## Visualizations

- Pie Chart: Used to represent the distribution of accidents by type of road and weather conditions.
- Funnel Chart: Visualize the casualties according to the road surface( Dry, Wet, Snow, Frost or ice, Flood)
- Bar Chart: Compare the number of casualties by road type.
- Cards: Display key metrics such as total casualties, total deaths, and total injuries(slight,fetal,fatal,serious).
- Donut Chart: Similar to pie charts but used to show proportions within a single category, such as vehicle type.

## Data Sources

The data used in this dashboard is sourced from official road accident records for the years 2021 and 2022. Ensure that the data is clean and accurate before uploading it to Power BI using power query editor.

## Snap of Maximum number of casualties by road type. (using pie chart)
<img width="364" alt="Screenshot 2024-05-03 at 4 39 32 PM" src="https://github.com/rahil6218/PowerBI/assets/163023453/94f99177-6d27-4af6-9f08-dea84aba6bd8">

## Snap of total number of casultiies. (using card)
<img width="360" alt="Screenshot 2024-05-03 at 4 39 32 PM" src="https://github.com/rahil6218/PowerBI/assets/163023453/cb61d541-f3b1-4ca2-93ed-247a8f3250b4">

## Snap of comparison between 2021-20222(using bar)
<img width="433" alt="Screenshot 2024-05-03 at 4 39 32 PM" src="https://github.com/rahil6218/PowerBI/assets/163023453/9e27b651-676d-478d-af36-134cac00e572">

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Remove all the null values and errors for the columns and to check error use filter option.
- Step 4 : After that make a conditonal column of the column i.e Vehicle type. Which has data that is car of any type which comes under car , all motorcycle above 500 cc and below 500 cc which comes under bikes and all mini bus and bus which come under Bus and all Good carrier of 5 tons or 3.5 tones comes under Good carriers
- Step 5 : Then close and save the filtered data to power bi.
- Step 6 : Then by using the line and stacked column chart represent the comparison between the casualties between 2021-2022 by putting on x-axis the accident_date column and on y-axis the number_of_casulties and on line axis the number of casualties.
- Step 7 : Then by using cards we represents the total number of type of casualties i.e fetal,serious,fatal,slight by placing accident severity in field.
- Step 8 : Then by using stacked bar chart we will compare the accident severity by putting accident severity on y-axis and Road type on x-axis.
- Step 9 : Then by using bar chart we calculated total number of casualties w.r.t to vehicle type by putting vehicle_type on x-axis and Number_of_casualties on y-axis.
- Step 10 : By using funnel chart we found the casualties by road surface condition by putting Road_surface_conditon in category and in value the Number_of_casualties.
- Step 11 : And by using pie chart we analyzed that how many number of accidents occur w.r.t to their road type. Putting Road_type in legend and Number_of_casualties in values.           


