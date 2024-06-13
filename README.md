# pwc-power-bi-internship

# Call Center Dashboard - Power BI Project

This project is part of my PwC Power BI internship. It involves creating a dashboard to visualize key performance indicators (KPIs) and metrics from a call center dataset.

## Introduction

### About phoneNow

phoneNow is a leading customer service provider dedicated to offering top-notch support across various service domains including contract management, technical support, payment assistance, administrative support, and streaming services. With a large team of agents handling numerous calls daily, phoneNow aims to deliver prompt and effective resolutions to customer inquiries and issues.

### Problem Statement

Despite its commitment to customer satisfaction, phoneNow has been facing challenges in effectively monitoring and optimizing its call center operations. The management team at phoneNow seeks better insights into their key performance indicators (KPIs) to identify areas for improvement, enhance agent performance, and ultimately boost overall customer satisfaction.

The specific goals are:
1. **Overall Customer Satisfaction:** Understand the current satisfaction levels of customers and identify trends.
2. **Calls Answered/Abandoned:** Monitor the ratio of answered to abandoned calls to improve call handling processes.
3. **Calls by Time:** Analyze call volumes by time to ensure optimal staffing and resource allocation.
4. **Average Speed of Answer:** Reduce the time taken to answer calls to improve customer experience.
5. **Agent Performance:** Evaluate individual agent performance based on average talk duration and the number of calls answered to provide targeted training and support.

To address these goals, a comprehensive Power BI dashboard will be developed to visualize these KPIs and provide actionable insights for phoneNow's management team.

## Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:
1. **Overall Customer Satisfaction**
2. **Calls Answered/Abandoned**
3. **Calls by Time**
4. **Average Speed of Answer**
5. **Agent Performance Quadrant (Average Handle Time vs Calls Answered)**

## Steps to Create the Dashboard

### Step 1: Data Import and Preparation

1. Open Power BI Desktop.
2. Click on "Home" > "Get Data" > "Text/CSV" and select the CSV file containing the dataset.
3. Load the data into Power BI.

### Step 2: Creating Measures and KPIs

#### Overall Customer Satisfaction
Create a measure for overall customer satisfaction:
```DAX
Overall Customer Satisfaction = AVERAGE(CallCenter[Satisfaction rating])
