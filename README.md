#### ![image](https://github.com/Chiikar/PWC-Call-Centre-Analysis/assets/156119801/5c22ab54-78d2-45aa-a665-38a97599b075)


# CALL CENTRE ANALYSIS

## DATA UNDERSTANDING 
This report presents a thorough examination of Phonenow's call center data for the fiscal year 2021, aiming to unveil enduring trends and patterns within call center operations. Utilizing exploratory data analysis (EDA) techniques, the analysis delves into various metrics such as call volume, durations, and peak call times, to provide valuable insights into Phonenow's strategic planning and decision-making processes. The analysis explores trends indicative of shifts in customer behavior, operational efficiency, or areas necessitating improvement within the call center. Key focus areas include identifying patterns in call volume and duration, seasonal variations, and any significant events or trends impacting call center performance throughout the year. The insights gleaned from this analysis will guide Phonenow's growth strategies, aid in optimizing call center operations, and contribute to enhancing customer satisfaction. The ensuing strategic recommendations will empower Phonenow to effectively leverage its call center data for sustained business success and overall performance improvement.

## INTRODUCTION
The dataset under analysis is sourced from Phonenow's telecommunications call center operations, encompassing customer interactions over the specified timeframe. Comprising 5000 rows and columns with diverse attributes such as Call ID, Agent, Date, Time, Topic, Answered (Y/N), Resolved, Speed of answer in seconds, Avg Talk duration, and Satisfaction rating, this dataset offers profound insights into the operational dynamics of Phonenow, the telecommunications firm.

## PROJECT GOAL
This project aims to analyze Phonenow's call center data for the fiscal year 2021 to identify enduring trends and patterns in call center operations. Through gaining insights into call volume, durations, peak call times, and other pertinent metrics, the goal is to provide strategic recommendations for optimizing call center operations, enhancing customer satisfaction, and driving business growth. Leveraging exploratory data analysis (EDA) techniques, actionable insights will be unearthed to inform Phonenow's decision-making processes and facilitate effective utilization of call center data for long-term success.


DATA SOURCES 
The primary dataset utilized for this analysis originates from the "Call-Centre-Dataset.xlsx" provided by PWC, capturing customer interactions over a designated timeframe at Phonenow's call center.

## TOOLS USED
- EXCEL: For data cleaning and analysis.
- POWER BI: For report creation.

## DATA CLEANING PROCESS


- Upon initial inspection of the raw dataset, Power Query was utilized to check for duplicates, resulting in none being found.
- The dataset comprises 5001 rows, including the header, and 10 columns.
- No inconsistent data or characters were observed within the dataset.
- Null values were identified in the Speed of answer in seconds, Satisfaction ratings, and AvgTalkduration columns.
- To enhance clarity, the column name 'answered(Y/N)' was renamed to 'Call Answered (Yes/No)', with 'Y' and 'N' values replaced by 'Yes' and 'No'.
- The 'Resolved' column name was renamed to 'Resolved (Yes/No)', with 'Y' and 'N' values replaced by 'Yes' and 'No'.
- Null values in the Satisfaction rating column were replaced with '0',The speed of answer in seconds column wa also replaced with '0', while those in the AvgTalkDuration column were retained to maintain data integrity.

### RESULT 
The cleaned dataset was imported into Power BI for data visualization and subsequent analysis.

 

## EXPLORATORY DATA ANALYSIS(EDA)
A dashboard reflecting all relevant Key Performance Indicators (KPIs) and Metrics in the Dataset was created in Power BI. The KPIs for this exploratory analysis encompass: 
- Overall Customer Satisfaction
- Overall Call Answered/Abandoned
- Calls by Time
- Average speed of answer
- Average Performance Quadrant (Talk Durations vs Calls answered)
- Total number of call ID 


## RESULTS
- Total Number of Call IDs: 5000
- Average speed of answer in seconds: 54.75 seconds
- Overall Customer Satisfaction: 2.76
- Overall calls answered: Yes (4.05k) - 81.08%, No (0.95k) - 18.92%
- Overall Issues Resolved: Yes (3.65k) - 72.92%, No (1.35k) - 27.08%
- Number of calls by month: January - Yes (1455), No (317); February - Yes (1298), No (318); March - Yes (1301), No (311).

 


## CONCLUSION
The analysis of Phonenow's call center data for the fiscal year 2021 has provided valuable insights into the company's operational dynamics and customer interactions. Through exploratory data analysis (EDA) techniques, key performance indicators (KPIs) such as call volume, call durations, overall customer satisfaction, and call resolution rates have been evaluated. The analysis has identified trends and patterns that can inform strategic decision-making processes to optimize call center operations, enhance customer satisfaction, and drive business growth.


## RECOMMENDATION
Based on the insights gained from the analysis, the following recommendations are proposed to Phonenow:
1. Improve Call Answering Efficiency: Given that approximately 18.92% of calls were not answered, Phonenow should focus on improving call handling processes to ensure a higher percentage of calls are answered promptly. This could involve optimizing staffing levels, implementing call routing strategies, or providing additional training to call center agents.
2. Enhance Call Resolution Rates: While the majority of issues were resolved (72.92%), there is still room for improvement. Phonenow should analyze the reasons for unresolved issues and implement measures to address them effectively. This may include providing agents with access to better resources or streamlining escalation procedures.
3. Monitor Customer Satisfaction: With an overall customer satisfaction rating of 2.76, Phonenow should closely monitor customer feedback and satisfaction levels to identify areas for improvement. Implementing regular customer satisfaction surveys or feedback mechanisms can help Phonenow gather valuable insights and address any issues or concerns raised by customers promptly.
4. Optimize Call Center Performance: Phonenow should leverage insights from the analysis to optimize call center performance. This could involve adjusting staffing levels or schedules to align with peak call times, implementing strategies to reduce the average speed of answers, or identifying opportunities to improve agent productivity and efficiency.
5. Utilize Data Visualization Tools: Phonenow should continue to utilize data visualization tools such as Power BI to monitor key performance indicators and track progress over time. Creating dashboards that provide real-time insights into call center operations can help Phonenow make data-driven decisions and drive continuous improvement initiatives.









 


