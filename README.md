# 📊 IT Support Analytics Dashboard – Power BI Project

##  Project Overview
The IT Support Analytics project analyzes IT support ticket data to understand ticket trends, SLA performance, agent productivity, and operational inefficiencies using Power BI.

The objective of this project is to provide actionable insights that help organizations improve IT service efficiency and decision-making.

---

## Business Objectives
- Analyze IT ticket volume and trends
- Measure SLA compliance and breach rates
- Evaluate agent performance and productivity
- Identify operational bottlenecks and backlog issues
- Provide insights to improve IT support processes

---

## Tools & Technologies
- Power BI – Data visualization & dashboarding  
- Power Query – Data cleaning & transformation  
- DAX (Data Analysis Expressions) – KPI and measure creation  
- Excel / CSV – Dataset source  

---

##  Dataset Description
- Source: IT Support Ticket Dataset  
- Records: 300+ tickets  
- Key Columns:
  - Ticket_ID  
  - Created_Date, Resolved_Date  
  - Category, Sub_Category  
  - Priority, Status  
  - Agent_Name, Department  
  - Resolution_Time_Hours  
  - SLA_Status  

---

##  Data Modeling
A Star Schema data model was implemented to improve performance and analytical flexibility.

### Fact Table:
- Fact_Tickets

### Dimension Tables:
- Dim_Date  
- Dim_Agent  
- Dim_Category  
- Dim_Department  
- Dim_Priority  

---

## Key DAX Measures
- Total Tickets  
- Resolved Tickets  
- Open Tickets  
- Backlog Tickets  
- SLA Met Tickets  
- SLA Breached Tickets  
- SLA %  
- Avg Resolution Time  
- Resolution Rate %  
- High Priority Tickets  
- Critical Priority Tickets  
- Agent Performance Metrics  

---

##  Dashboards Created

### 1. Overview Dashboard
- Ticket volume trends  
- SLA compliance status  
- Category and priority analysis  
- Key operational KPIs  

![image](https://github.com/Aishwarya-work/IT-Support-Analytics-PowerBI/blob/main/IT%20support%20analytics%20overview.png)

### 2. Agent Performance Dashboard
- Tickets handled by each agent  
- SLA compliance by agent  
- Resolution efficiency  
- Agent-wise performance comparison  

![image](https://github.com/Aishwarya-work/IT-Support-Analytics-PowerBI/blob/main/Agent%20performance%20dashboard.png)

### 3. SLA & Operations Dashboard
- SLA trends over time  
- Resolution time distribution  
- Department-wise ticket analysis  
- SLA breach analysis  

![image](https://github.com/Aishwarya-work/IT-Support-Analytics-PowerBI/blob/main/SLA%20and%20performace%20dashboard.png)
---

##  Key Insights
- Only ~22% of tickets met SLA, indicating operational inefficiencies.  
- Backlog tickets are significantly higher than resolved tickets.  
- High and critical priority tickets contribute heavily to workload.  
- Agent performance varies significantly across agents.  
- Certain departments generate more tickets, highlighting process gaps.  

---

##  Business Recommendations
- Strengthen SLA monitoring and escalation mechanisms.  
- Optimize workload distribution among agents.  
- Prioritize high and critical tickets.  
- Improve processes in high-ticket departments.  
- Introduce automation and self-service for repetitive issues.  

---

## Conclusion
This project demonstrates how Power BI can be used to analyze IT support operations, identify inefficiencies, and support data-driven decision-making.

The dashboards provide a comprehensive view of IT support performance and help organizations improve service quality and operational efficiency.

---

## Author

Aishwarya M

Data Enthusiast | Power BI | SQL

