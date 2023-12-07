# E-commerce-Analytics
A project in Google Sheets to analyze sales data and communicate findings in a way that executives can understand easily.  
[Project Link](https://docs.google.com/spreadsheets/d/10b5HvXs2XzCHScZjHYnhYyKPGJEpNpwGi2lTrieSl40/edit#gid=38637670)
## Introduction
### Company Overview
In response to the increasing need for data-driven decision-making, an e-commerce company embarked on the "E-commerce Analytics Enhancement" project, appointing an analyst to transform raw transaction logs into actionable business metrics.
### Objective
The primary focus of the project is to gain comprehensive insights into user behavior, optimize conversion funnels, and refine retention strategies. My role encompassed constructing a conversion funnel, preparing data for cohort analysis, and calculating retention rates to empower the executive team with valuable insights for strategic decision-making.

## Project Analysis
**Building a Conversion Funnel:**  
- Created a conversion funnel using data from the “raw_user_activity” sheet
- The funnel, named “conversion_funnel,” comprises three stages, showcasing user interactions with the website
- Implemented formulas to calculate total conversion rates and conversion rates to the next step
- Utilized advanced spreadsheet techniques to ensure accurate counting of unique users at each stage

**Data Preparation for Cohort Analysis:**
- Filtered purchase events from the “raw_user_activity” sheet and created a new sheet named “purchase_activity”
- Isolated 4,845 rows of purchase data, including column headers
- Calculated the first purchase dates for each user and transferred them to the “purchase_activity” sheet
- Created three new columns—`event_month`, `first_purchase_month`, and `cohort_age`—to facilitate cohort analysis
 
**Calculating Retention Rates:**
- Grouped purchase data into cohorts using a pivot table in the “cohort_analysis” sheet
- Configured the pivot table to represent six cohorts based on the month of customers' first purchases
- Created a new sheet, “retention_rates,” to calculate and present overall retention rates
- Applied formulas to calculate retention rates for each cohort at different cohort ages

**Organizing and Documenting the Spreadsheet:**
- Filled in the results synopsis and analysis descriptions in the “Executive Summary” sheet
- Reordered sheet tabs for optimal organization, placing “Table of Contents” and “Executive Summary” first
- Formatted spreadsheets for readability, including number and date formatting, table borders, bold headers, and frozen rows
- Ensured the spreadsheet is polished and professional for presentation to the executive team

## Executive Summary
### Conclusion
**Cohort Analysis and User Age Dynamics**: The observation that the first cohort group possesses the smallest user count but exhibits the longest user age of 4 months implies a potential trend of user longevity despite a modest initial user base.

**Retention Rate Trends**: Retention rates peak in the first month across all cohort groups and gradually decline in subsequent months, with an exception noted for the 2020-09 cohort.The identified trend could prompt further investigation into factors contributing to the unsual pattern in the 2020-09 cohort. Insights may uncover specific strategies or user behaviors affecting retention dynamics.	

### Suggestions for Further Improvement or Business Outcomes
1. **Enhance Initial Cohort Engagement:**  
    - *Suggestion:* Implement targeted marketing or onboarding strategies for new users to boost the initial cohort size, considering the potential for longer user retention observed in the first cohort group. 
    - *Expected Outcome:* Increased user acquisition and potentially higher long-term retention, positively impacting overall customer lifetime value. 
2. **Investigate Anomalies in Retention Rates:**  
    - *Suggestion:* Conduct a detailed analysis of the 2020-09 cohort to identify factors contributing to its unique retention rate trend. Investigate product launches, marketing campaigns, or user experience changes during that period. 
    - *Expected Outcome:* Uncover insights into specific elements influencing user behavior, enabling the company to replicate successful strategies or address issues affecting retention. 
3. **Optimize Retention Strategies Beyond the First Month:**  
    - *Suggestion:* Develop targeted retention strategies for months beyond the initial phase, aiming to sustain user engagement. Implement personalized communication, loyalty programs, or feature enhancements to address potential drop-offs. 
    - *Expected Outcome:* Mitigate the observed decline in retention rates over time, fostering prolonged user engagement and increasing overall customer loyalty. 
4. **Implement A/B Testing for User Experience:**  
    - *Suggestion:* Conduct A/B testing on the website's user interface, navigation, or checkout process to identify elements that positively impact conversion rates. Implement changes based on successful outcomes. 
    - *Expected Outcome:* Improved conversion rates at various stages of the sales process, contributing to a more seamless user experience and potentially higher overall sales. 
5. **Iterative Analysis and Continuous Monitoring:**  
    - *Suggestion:* Establish a routine for iterative cohort analysis and continuous monitoring of user behavior. Regularly update the analysis based on new data, allowing the company to adapt strategies in response to evolving trends.  
    - *Expected Outcome:* Timely identification of changing user patterns and the ability to proactively adjust business strategies to align with user preferences and market dynamics.  

Implementing these suggestions can contribute to a more proactive and data-driven approach, fostering continuous improvement in user engagement, conversion rates, and overall business performance for the e-commerce company.
