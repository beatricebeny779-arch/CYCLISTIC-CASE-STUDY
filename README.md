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



**Business Task**: Cyclistic aims to increase annual memberships. The marketing team wants to understand differences in riding behavior between casual riders and annual members to develop effective marketing strategies.

Business Task









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

