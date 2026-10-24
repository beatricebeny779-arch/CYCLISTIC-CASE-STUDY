## CYCLISTIC-CASE-STUDY

## Project Overview

The Cyclistic Case study is a capstone project from the Google Data Analytics Professional Certificate on Coursera. It explores how casual riders and annual members use Cyclistic's bike-sharing service differently.

### Business Scenario

In 2016, Cyclistic company launched a successful bike-share offering. The company’s success depends on maximizing the number of annual memberships. The marketing team wants to understand differences in riding behavior between casual riders and annual members, and  from these insights, your team will design a new marketing strategy to convert casual riders into annual members.

The case study follows the six step data analysis process

❓ Ask

📋 Prepare

🛠️ Process

📊 Analyze

📢 Share

🚴 Act

**1. ASK**
---

**Business Task**: Cyclistic aims to increase annual memberships. The marketing team wants to understand differences in riding behavior between casual riders and annual members to develop effective marketing strategies.

**Primary Stakeholders**: The director of marketing Lily Moreno and the Cyclistic Executive team.

**Secondary Stakeholders**: The Cyclistic marketing analytics team.

DELIVERABLE: A clear statement of Business task


**2.	PREPARE**
   
Data Source: 12 months dataset (September 2025 to August 2026) of Cyclistic trip data from Motivate International Inc. [data source](https://divvy-tripdata.s3.amazonaws.com/index.html) with a public [license](https://www.divvybikes.com/data-license-agreement).

The dataset has 12 CSV files, 14 columns and 6.1 million rows. The data also follows the **ROCCC** Approach.

**Reliability**: the data includes complete and accurate ride data from Divvy. Divvy is a program of the Chicago Department of Transportation (CDOT), which owns the city’s bikes, stations and vehicles.

**Original**: the data is from Motivate International Inc, which operates the City of Chicago’s Divvy bike sharing service.

**Comprehensive**: The data includes types of bikes, start and end station name, start and end time, station ID, station longitude and latitude, and membership types.

**Current**: data is up to date to August 2026

**Cited**: the data is cited and under license agreement.


**3. PROCESS**

Data Cleaning Process, 

**Tool used**: Excel Power Query

I used Excel Power Query to combine and clean the 12 monthly CSV files. The cleaning pipeline involved five stages.

1. Combined all the 12 monthly CSV files from the source folder and stacked into a single query using Power Query's features.

2. Converted data types, `started_at` and `ended_at` were converted from text to Date/Time; rows with unparseable dates were removed.

3. Added the **`ride length`** - a custom column calculated as`Duration.TotalMinutes([ended_at]-[started_at])` in minutes.

4. Added **`month`** and **`day_of_the week`** using Power Query's Date functions.

5. Removed outliers- the rides that were under 1 minute(false starts) or over 24 hours (lost/stolen bikes) were filtered out to prevent distortion of the averages.






The 12 monthly CSVs were cleaned in Python using the pandas library, the following tasks were performed;

- 
















## Table of Contents 

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning-Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results / findings](#results--findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- 

## Project Overview

The Cyclistic Case study is a capstone project from the Google Data Analytics Professional Certificate on Coursera. It presents a real-world scenario where data analysts examine how different customer segments use cyclistic’s bike sharing services.

Cyclistic is a fictional bike share company based in Chicago, and the dataset provided for this case study is provided by Motivate International inc under a public license. The goal of this analysis is to uncover usage patterns, compare customer behaviors, and provide data driven recommendations to convert casual riders into annual members.

### Data Sources
Bike Data: The primary dataset used for this analysis is the "2025_divvy_trip_data. 12 CSV" files containing 5.5M rows of ride data.

### Tools
- Microsoft Excel - Data Cleaning [Download here](https://microsoft.com)
- SQL- Data Analysis [Download here](https://microsoft.com)
- Tableau- Creating Reports [Download here](https://microsoft.com)

### Data Cleaning/Preparation
In the initial data preparation phase , I performed the following tasks:
1. Data loading and Inspection.
2. Handling missing values.
3. Filtering system-generated ghost files.
4. Data Cleaning and formatting (formatting text to Date/Time).

### Exploratory Data Analysis
EDA involved exploring the Chicago cyclistic bike data to answer key questions such as:
- How do annual members and casual riders use Cyclistic bikes differently?
- Why would casual riders buy Cyclistic annual memberships?
- How can Cyclistic use digital media to influence casual riders to become members?

### Data Analysis
Include some interesting codes/features worked with
```Sql
SELECT 
  AVG(TIMESTAMP_DIFF(ended_at, started_at, MINUTE)) AS mean_ride_length,
  MAX(TIMESTAMP_DIFF(ended_at, started_at, MINUTE)) AS max_ride_length
FROM `project-01453ee1-45c5-4ba5-b6f.2025_trip_dataset.bike_trips`;
```

### Results/Findings
Hapa elezea ulichokikutaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
Analysis can also be summarized as follows, you can do numbering
1. 
2.  
3. 

### Recommendations
The actions you recommend for the company to take in order for them to increase their revenues.
- nnnnnnn
- nnnnnnn
- kkkkkkk

### Limitations
Maybe you had to remove or exclude some records during your analysis because maybe they would affect the accurracy of your analysis etc. So anything that you did to modify the data and exclude some records you can mention them in your limitations so that whoever is looking at your analysis can have context and know how much they can actually rely on it. 

### References
1. SQL for Businesses by Wangwan
2. [Stack Overflow](https://stackoverflow.com)

😆

💻

🔥
|Heading1|Heading2|Heading3|
|--------|---------|--------|
|Content1|Content2|Content3|
|Python|SQL|Excel|

`column 1`

**bold**

*italic*

