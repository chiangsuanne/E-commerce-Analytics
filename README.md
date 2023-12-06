# E-commerce-Analytics
A project in Google Sheets to analyze sales data and communicate findings in a way that executives can understand easily.  
[Project Link](https://docs.google.com/spreadsheets/d/10b5HvXs2XzCHScZjHYnhYyKPGJEpNpwGi2lTrieSl40/edit#gid=38637670)

## Project Overview
An e-commerce company offers a wide range of products. With a focus on providing a seamless user experience, the company captures detailed event logs of user activities on its website. As part of its commitment to data-driven decision-making, the company was looking to transform raw transaction logs into valuable business metrics. My primary tasks included building a conversion funnel, preparing data for cohort analysis, calculating retention rates, and organizing the findings into a polished spreadsheet for presentation to the executive team.

## Methodology, Technique, Result
**Building a Conversion Funnel:**  
I created a conversion funnel using data from the “raw_user_activity” sheet. This specific funnel, named “conversion_funnel,” comprises three stages, capturing user interactions with the website. Through the implementation of advanced spreadsheet techniques and formulas, I ensured accurate tracking of unique users at each stage, presenting total conversion rates and conversion rates to the next step.  

**Data Preparation for Cohort Analysis:**
Following the establishment of the conversion funnel, I prepared data for cohort analysis. By filtering purchase events from the “raw_user_activity” sheet and creating a dedicated “purchase_activity” sheet, a focused dataset of 4,845 rows, including column headers, was isolated. The subsequent calculation of first purchase dates for each user and the creation of three pivotal columns - ‘event_month’, ‘first_purchase_month’, and ‘cohort_age’ - positioned the project for insightful cohort analysis.   
 
**Calculating Retention Rates:**
Grouping the purchase data into cohorts using a pivot table on the “cohort_analysis” sheet, I configured the table to represent six cohorts based on the month of customers’ first purchases. This arrangement allowed for the calculation and presentation of overall retention rates in a new sheet, “retention_rates” offering a detailed perspective on user engagement over time.  

**Organizing and Documenting the Spreadsheet:**
Finally, to ensure the project’s presentation met professional standards, I organized and documented the spreadsheet. The “Executive Summary” sheet was enriched with a results synopsis and analysis descriptions, summarizing findings from cohort analysis and retention rates. The entire spreadsheet was formatted for readability for an overall polished appearance conducive to executive review.  

## Executive Summary
### Results
**Cohort Analysis**: The first cohort group has the smallest number of users, but has the longest age of user of 4 months. 	

**Retention Rates**: Retention rates are highest after the first month and then continue to decrease throughout the months for each cohort group, excluding the 2020-09 group. 		

### Analysis
**Raw Data**: The raw data includes the timeframe starting 2020-09 through 2021-02. There are three event activities. Each time a user views a product page, opens their shopping cart, or completes a purchase, the event is captured in the activity logs. We filtered for purchase activities since we are interested understanding conversion of product views into purchases and tracking month by month cohort metrics based on the month of a user's first purchase. After filtering, our columns of focus were user_id and event_date. 		

**Conversion Funnel**: Using the raw data, the unique count of user ids of each event was determined to calculate the total conversion rates and the conversion rates in the funnel of next steps.	

**Retention Rates**: To calculate retention rate, the number of users in each cohort were grouped by the unique values of each user id for the starting cohort depending on the month of a user's first purchase. Month by month cohort metrics were calculated by aggregating the unique values of user id within the difference of number of months between the first purchase and the respective purchases. Retention rate was calculated by dividing the number of month to month cohort sizes from the starting cohort size as a percentage value. 	
