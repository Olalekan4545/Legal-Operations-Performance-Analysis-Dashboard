# ⚖️ Legal-Operations-Performance-Analysis-Dashboard
The Legal Operations Performance Dashboard is an interactive Power BI report developed to analyze the operational, financial, and client performance of a fictional law firm. The dashboard enables stakeholders to monitor key business metrics, evaluate legal case performance, assess lawyer productivity, and identify opportunities to improve profitability and operational efficiency.



This project was created as part of a ZoomCharts Power BI Challenge, demonstrating advanced data modeling, DAX calculations, interactive reporting, and storytelling with data.

</tr>
    <tr>
      <td>🌐</td>
      <td><a href="">View Live Dashboard</a></td>   |      </tr>
    <tr>
      <td>📃</td>
      <td><a href="https://docs.google.com/spreadsheets/d/1XgcfQcdCkTI5AEU1u2pO4-lz6zfdRS0D/edit?usp=drive_link&ouid=104203473424749821517&rtpof=true&sd=true">Dataset</a></td> |    <tr>
      <td>👤</td>
      <td><a href="https://linkedin.com/in/afolakemi-olalekan-145174253">Linkdin Profile</a></td>   |   </tr>
    <tr>
      <td>🌐</td>
      <td><a href="https://olalekan4545.github.io/Port-folio/">Portfolio</a></td>


## 🎯 Business Objective

The objective of this dashboard is to help decision-makers answer key business questions such as:

- How is the law firm performing financially?
- Which practice areas generate the highest revenue and profit?
- How efficiently are legal cases managed?
- Which lawyers contribute the most value?
- Which clients and industries generate the highest revenue?
- How are risk, workload, and lawyer utilization distributed across the firm?

## 📄 Dataset Description
The dataset is a fictional legal operations dataset consisting of six related tables that model the activities of a law firm. It captures information on legal cases, lawyers, clients, office locations, and calendar dates, enabling comprehensive analysis of business performance and operations.

The data includes:

- Fact_Cases: Transactional data containing case details, billable and non-billable hours, revenue, internal costs, profit, outstanding balances, client satisfaction, risk scores, lawyer utilization, and workload metrics.
- Dim_Case: Case attributes such as case status, outcome, complexity, practice area, case type, and priority.
- Dim_Lawyer: Lawyer information including seniority, department, years of experience, gender, and employment status.
- Dim_Client: Client details such as industry, company size, country, region, strategic client status, and client tenure.
- Dim_Office: Office locations with city, country, region, and geographic coordinates for map-based analysis.
- Dim_Date: A calendar table supporting time-based analysis by day, week, month, quarter, fiscal period, and year.

The dataset was modeled using a star schema in Power BI, with Fact_Cases serving as the central fact table connected to the dimension tables through primary and foreign key relationships. This structure supports efficient reporting, interactive filtering, and detailed analysis across legal operations, financial performance, lawyer productivity, and client management.


# 📊 Dashboard Pages

1. ## Executive Overview

Provides a high-level summary of the firm's performance through KPIs and interactive visuals.

Key Metrics

- Total Revenue
- Total Profit
- Total Cases
- Profit Margin
- Outstanding Balance
- Average Client Satisfaction

2. ## Case Performance & Efficiency

Analyzes legal case operations and performance.

Insights Include

- Cases by Practice Area
- Case Status Distribution
- Case Complexity Analysis
- Duration Group Analysis
- Billable Hours vs Profit
- Top 10 Revenue-Generating Cases

3. ## Lawyer & Client Performance

Evaluates lawyer productivity and client value.

Insights Include

- Revenue by Lawyer
- Lawyer Utilization
- Client Satisfaction
- Revenue by Industry
- Strategic vs Non-Strategic Clients
- Lawyer Performance Table

4. ## Financial & Operational Insights

Focuses on financial health and operational efficiency.

Insights Include

- Profit by Practice Area
- Outstanding Balance by Client
- Revenue by Risk Category
- Profit by Revenue Band
- Workload Distribution
- Financial Performance Summary

# 🛠️ Tools Used

- Power BI Desktop
- Power Query
- DAX
- ZoomCharts Custom Visuals
- Microsoft Excel

 
# 📈 Key Features

- Interactive drill-down analysis
- Dynamic KPI cards
- Geographic office analysis
- Conditional formatting
- Executive-level dashboard design
- Cross-filtering across visuals
- Data-driven storytelling

# 💡Key Skills Demonstrated

- Data Cleaning with Power Query
- Data Modeling
- DAX Measure Development
- Business Intelligence
- Dashboard Design
- Data Visualization
- Business Storytelling
- Interactive Reporting
- Performance Analysis

