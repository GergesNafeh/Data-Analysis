# Call Center Analysis Dashboard

## Overview
 This project contains an interactive **Excel dashboard** for analyzing call center performance, built using PivotTables, Power Query, and Excel charts. 

 ### 🚀 Features
- Sentiment Analysis of Calls (Positive, Negative, Neutral, etc.)
- Calls by Reason (Billing, Payments, Service Outage)
- Time Response per Call (SLA performance)
- Calls by Day (trend analysis)
- KPI Report with:
  - Total Calls
  - Average Handling Time (AHT)
  - Average NPS
  - Channels of Calls (Web, Email, Chatbot, Call Center)
  - Top 3 Calling States (USA map)


#### 🛠 Tools Used
- Microsoft Excel (PivotTables, Power Query, Charts, Conditional Formatting)
- Data Cleaning & Preparation in Excel
- Visualization techniques for KPIs

#### Data Cleaning
- Removed duplicates and irrelevant records.  
- Standardized date formats (DD/MM/YYYY).  
- Fixed missing values (replaced nulls with appropriate values or removed rows when necessary).  
- Normalized call reason categories (e.g., “Billing Questions” vs “Billing Query” → unified as “Billing Question”).  
- Split columns for better analysis (e.g., separating Call Center location into City/State).  
- Ensured numerical fields (AHT, NPS, SLA times) were in the correct format.  
- Created a **CleanedData_source** sheet to store processed data for pivot tables.  

#### 📈 Insights
- Most common call reason: **Billing Questions**
- SLA breaches mostly occurred in **Los Angeles/CA**
- Majority of calls came through **Call Center & Chatbot**
- **NPS scores** show room for improvement in customer satisfaction.

## business questions
 This dashboard helps to answer key business questions such as:

1. **What are the main reasons customers call the contact center?**  
   → Billing Questions, Payments, and Service Outages.

2. **How is customer sentiment distributed across calls?**  
   → Positive, Negative, Neutral, Very Negative, Very Positive.

3. **Which call centers receive the most calls?**  
   → Baltimore/MD, Chicago/IL, Denver/CO, and Los Angeles/CA.

4. **How are calls trending over time (daily)?**  
   → Line chart shows fluctuations in call volume by day.

5. **How fast are calls being handled compared to SLA?**  
   → Breakdown of calls Above SLA, Below SLA, and Within SLA.

6. **What is the overall contact center performance?**  
   → KPIs such as Total Calls, Average Handling Time (AHT), and Average NPS.

7. **Which channels are customers using the most?**  
   → Call Center, Chatbot, Email, and Web.

8. **Which states have the highest call volumes?**  
   → Top 3 Calling States are highlighted on the US map.
