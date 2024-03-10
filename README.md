# Road-Accident-Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Transformation](#transformations)
- [EDA](#eda)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Recommendation](#recommendation)

### Project Overview
---

This data analysis aims to understand the trend of road accident, contributing factors, the type of  vehicle involved and casualities based on trends and weather conditions. By analysing various aspects of the data, we identified trends, make data driven recommendations, and gained a deeper understanding on road accident occurance and frequency within the region..

![Screenshot (5)](https://github.com/OgechukwuLily/Road-Accident-Analysis/assets/160866623/9b1cfdbd-68de-46d5-96fe-41942f2a138c)

### Data Sources
Road-Accidents: The primary dataset used for tis analysis is the 'Road Accident Data Data.xlsx'file containing detailed information about Road accident in the region.

### Tools
- Excel - Data cleaning
- PowerBI - Power Query
- PowerBI - creating reports and visualization



### Transformations

In the initial data preparation phase, we perfomed thr following tasks:
1. data Loading and inspection
2. Handling missing values and duplicates
3. Data cleaning and formatting
 

### EDA

EDA involved in exploring the road accident data to answer questions such as:

- What is the Current Year Accidents and Casualties?
- What is the values of the nature of the casualties?
- What is the Current year vs Previous Year casaulties monthly trend?
- What is the casualties by Road_type?
- What is the casualties by Vehicle Types?
- what is the Casualties by location?
    
### Data Analysis
```PowerBI
 Previous Year Accident = CALCULATE(COUNT('Data Cleaning'[Accident Date]),SAMEPERIODLASTYEAR(Xcalender[Date]))
 ```

### Insights
The analysis insights are summarized as follows:
1. The current year accident and causlties is on the hingh side with 16.3% chance of occuring
2. Cars are the mature vehicle type involed in most accident occurance.
3. Most accidents occur in daylight than in darkness with 73.8% chance of occurance.
4. Single and dual carriage way are the major contributing factors of road accident while roundabout andone way street and slip road are least'

### Recommendation
      
Based on the analysis, we recommend the following actions:
- Traffic wardens should be place and positioned in all roundabouts single and dual carriageways to assist in  directing traffics
- Cars and buses needs to be inspected periodically for breakpads functionality
- Over-speeding tickets and stiff measures should be recommended on roads over 30mph
- The driveway needs to be widened to accommodate more passage.
      
 
