# Divvy Bicycle Trip Analysis

## Project Overview
This project analyzes the last 12 full months of Divvy bicycle trip data to identify behavioral differences between **annual members** and **casual riders**.

The goal of the analysis is to uncover usage patterns related to ride frequency, ride duration, and time-based behavior, and to generate insights that could support **business and marketing decisions**.

---

## Business Task
The objective of this project is to understand how **annual members** and **casual riders** use Divvy bicycles differently.

By identifying key behavioral differences, this analysis aims to support strategies that could help **convert casual riders into annual members**.

---

## Data Source
The data used in this project comes from the official Divvy trip dataset:

- Source: [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html)

The notebook automatically downloads and combines the **last 12 full months** of available trip data.

---

## Tools and Technologies
This project was built using:

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Requests**
- **ZipFile**

---

## Project Workflow
The analysis follows these main steps:

1. **Data Collection**
   - Download monthly ZIP files directly from the Divvy data source
   - Extract and combine trip data into a single dataset

2. **Data Cleaning**
   - Convert date and time columns
   - Calculate ride duration in minutes
   - Remove invalid and unrealistic rides

3. **Feature Engineering**
   - Extract date, month, day of week, and hour of day
   - Prepare data for behavioral analysis

4. **Exploratory Data Analysis**
   - Compare member and casual rider usage
   - Analyze ride duration and ride counts
   - Explore usage patterns by weekday and hour

5. **Visualization**
   - Ride frequency by day of week
   - Ride frequency by hour of day

6. **Insights and Recommendations**
   - Identify behavioral differences
   - Generate business-oriented recommendations

---

## Key Insights
Some of the main findings include:

- **Annual members** use the service significantly more frequently than **casual riders**
- **Casual riders** tend to have longer average ride durations
- **Members** show stronger weekday usage patterns, suggesting commuting behavior
- **Casual riders** are more active on weekends, suggesting leisure-oriented usage
- These differences indicate a potential opportunity to convert casual riders into annual members

---

## Recommendations
Based on the analysis, the following recommendations were identified:

- Develop targeted campaigns for frequent casual riders
- Offer incentives such as membership discounts or trial memberships
- Improve availability during peak commuting hours for members
- Create offers specifically tailored to weekend and leisure users

---

## Repository Structure# Divvy-Bicycle-Trip-Analysis
Exploratory data analysis of Divvy trip data to uncover rider behavior patterns and business insights.
