# ⚖️ Legal-Operations-Performance-Analysis-Dashboard
The Legal Operations Performance Dashboard is an interactive Power BI report developed to analyze the operational, financial, and client performance of a fictional law firm. The dashboard enables stakeholders to monitor key business metrics, evaluate legal case performance, assess lawyer productivity, and identify opportunities to improve profitability and operational efficiency.



This project was created as part of a ZoomCharts Power BI Challenge, demonstrating advanced data modeling, DAX calculations, interactive reporting, and storytelling with data.

</tr>
    <tr>
      <td>🌐</td>
      <td><a href="https://app.powerbi.com/view?r=eyJrIjoiYTM3MzBlZDktOWYzOS00YTMxLWJiMzEtOTZkYjk4YWU2MzU0IiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9">View Live Dashboard</a></td>   |      </tr>
    <tr>
      <td>📃</td>
      <td><a href="https://docs.google.com/spreadsheets/d/1XgcfQcdCkTI5AEU1u2pO4-lz6zfdRS0D/edit?usp=drive_link&ouid=104203473424749821517&rtpof=true&sd=true">Dataset</a></td> |    <tr>
      <td>👤</td>
      <td><a href="https://linkedin.com/in/afolakemi-olalekan-145174253">Linkdin Profile</a></td>   |   </tr>
    <tr>
      <td>🌐</td>
      <td><a href="https://olalekan4545.github.io/Port-folio/">Portfolio</a></td>


## Table of Contents
- Overview
- Business Objectives
- Dataset Description
- Dashboard Pages
- Tools used
- Key Metrics
- Measures
- Key Features
- Key Skills Demostrated
- Insights & Recommendations
- How to Use the Report
   
#

## 📌 Project Overview
**Legal Operations Performance Analysis-Dashboard** is an interactive 4 Pages Power BI dashboard that analyze the operational, financial, and client performance of a fictional law firm.


<table>
  <tr>
    <th>Dataset Information</th>
    <th>Value</th>
   </tr>
  <tr>
    <td>Source</td>
    <td>zoomchart Challenge Dataset</td>
  </tr>
  <tr>
    <td>Tool</td>
    <td>Microsoft Power Bi</td>
  </tr>
  <tr>
    <td>Dataset</td>
    <td> The Spreadsheet Consists of 6 Tables which Includes Fact_Cases, Dim_Clent, Dim_Lawyer, Dim_Date, Dim_Cases, Dim_Office</td>
   </tr>
  <tr>
    <td>Date Range</td>
    <td>2024 - 2026</td>
   </tr>
  <tr>
    <td>Report Pages</td>
    <td>4</td>
      </tr>
      </tr>
  <tr>
    <td>Live Report</td>
     <td><a href="https://app.powerbi.com/view?r=eyJrIjoiYTM3MzBlZDktOWYzOS00YTMxLWJiMzEtOTZkYjk4YWU2MzU0IiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9">View Live Dashboard</a></td>
    </tr>
</table>

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


## 📊 Dashboard Pages

 #### Page 1 - Executive Overview

 This page was created to provide stakeholders with a high-level summary of the law firm's overall performance. This page highlights key business metrics such as revenue, profit, total cases, profit margin, outstanding balance, and client satisfaction, enabling executives to quickly assess the firm's health and make informed strategic decisions.
 

 ❓ Business Questions & Answered

Questions

- How is the law firm performing overall?
- What are the firm's total revenue, profit, and profit margin?
- How many legal cases are being managed?
- How many cases are open versus closed?
- What is the current outstanding balance?
- How satisfied are clients with the firm's services?
- Which practice areas and office locations contribute the most revenue?

Answers

- Provides a high-level overview of the firm's financial and operational performance.
- Highlights key performance indicators (KPIs) for quick executive decision-making.
- Identifies top-performing offices and practice areas.
- Shows the firm's current workload and overall client satisfaction.

Visual Includes:
- Revenue Trend
- Case Status Distribution 
- Revenue by Practice Area 
- Office Performance by Location

  
#### Page 2 - Case Performance & Efficiency
 This page was created to evaluate how effectively legal cases are being managed throughout their lifecycle. This page analyzes case volume, status, complexity, duration, billable hours, and profitability, helping management identify operational bottlenecks, monitor case progress, and improve overall case handling efficiency.

 ❓ Business Questions & Answered
 

 Questions

- Which practice areas handle the highest number of cases?
- What is the distribution of cases by status and outcome?
- How are cases distributed across different complexity levels?
- How long do cases typically remain open?
- Which cases generate the highest revenue and profit?
- Is there a relationship between billable hours and profit?
- Which case categories require the greatest operational effort?

Answers

- Identifies departments with the highest workload.
- Shows how efficiently cases progress through their lifecycle.
- Highlights the firm's most valuable and most complex cases.
- Reveals operational bottlenecks through case duration analysis.
- Evaluates whether increased legal effort results in higher profitability.


Visual Include:
- Cases by Practice Area
- Case Status Distribution
- Case Complexity Analysis
- Duration Group Analysis
- Billable Hours vs Profit
- Top 10 Revenue-Generating Cases

#### Page 3 - Lawyer & Client Performance
This Page was created to assess the performance of lawyers and understand client value across the firm. This page examines lawyer productivity, utilization, revenue contribution, client satisfaction, and client segmentation, enabling leaders to recognize top-performing lawyers, strengthen client relationships, and allocate resources more effectively.


 ❓ Business Questions & Answered

 Questions

- Which lawyers generate the most revenue?
- Which departments contribute the highest revenue?
- How effectively are lawyers utilized?
- Which industries generate the highest revenue?
- Are strategic clients more valuable than non-strategic clients?
- Which lawyers achieve the highest client satisfaction?
- Which clients contribute the most to the firm's success?

Answers

- Identifies top-performing lawyers and departments.
- Measures lawyer productivity and utilization.
- Evaluates client satisfaction across legal services.
- Highlights the firm's most valuable industries and client segments.
- Supports better resource allocation and client relationship management.


Visual Include:
- Revenue by Lawyer
- Lawyer Utilization
- Client Satisfaction
- Revenue by Industry
- Strategic vs Non-Strategic Clients
- Lawyer Performance Table

#### Page 4 - Financial & Operational Insights

This Page was created to analyze the firm's financial health and operational effectiveness. This page focuses on profitability, internal costs, outstanding balances, workload distribution, lawyer utilization, and risk levels, helping decision-makers optimize financial performance, improve cash flow, manage operational risks, and support long-term business growth.


❓ Business Questions & Answered


Questions

- Which practice areas generate the highest profit?
- Which clients have the highest outstanding balances?
- Which risk categories contribute the most revenue?
- Which revenue bands are the most profitable?
- How is the firm's workload distributed?
- Are lawyers underutilized, optimally utilized, or overutilized?
- Which operational areas require improvement?

Answers

- Measures the firm's financial performance and profitability.
- Identifies opportunities to improve cash collection.
- Evaluates the relationship between risk and revenue.
- Assesses workload balance and lawyer capacity.
- Provides actionable insights to improve operational efficiency, profitability, and long-term business performance.

Visual Include

- Profit by Practice Area
- Outstanding Balance by Client
- Revenue by Risk Category
- Profit by Revenue Band
- Workload Distribution
- Financial Performance Summary

## 🛠️ Tools Used

- Power BI Desktop
- Power Query
- DAX
- ZoomCharts Custom Visuals

## 📊 Key Metrics


<table>
  <tr>
    <th>Page Number</th>
   <th>Page 1(Executive Overview)</th>
   <tr>
    <th>KPIs</th>
   <th>Values</th>
    <tr>
    <th>Total Revenue</th>
   <th>€2.08bn</th>
     <tr>
    <th>Total Profit</th>
   <th>€1.59bn</th>
    <tr>
    <th>Total Cases</th>
   <th>15k</th>
    <tr>
    <th>Profit Margin(%) </th>
   <th>56.81%</th>
    <tr>
    <th>Open Cases</th>
   <th>8118</th>
     <tr>
    <th>Closed Cases</th>
   <th>6882</th>
    <tr>
    <th>Outstanding Balance</th>
   <th>€773.38M </th>   
    <tr>
    <th>Avg Client Satisfaction Score</th>
   <th>6.6</th>
    <tr>
   <th></th>
   </tr>
 <table>


<table>
  <tr>
    <th>Page Number</th>
   <th>Page 2 (Case Performance & Efficiency) </th>
   <tr>
    <th>KPIs</th>
   <th>Values</th>
    <tr>
    <th>Avg Days Open</th>
   <th>258</th>
    <tr>
    <th>Avg Billable Hours</th>
   <th>139.96</th>
    <tr>
    <th>Avg Court Apprearances</th>
   <th>0.78</th>
     <tr>
    <th>Avg Meetings</th>
   <th>5.35</th>
 </tr>
</table>

<table>
  <tr>
    <th>Page Number</th>
   <th>Page 3 (Lawyer & Client Performance) </th>
   <tr>
    <th>KPIs</th>
   <th>Values</th>
    <tr>
    <tr>
    <th>Total Lawyer</th>
   <th>200</th>
    <tr>
    <th>Total Client</th>
   <th>800</th>
   <tr>
    <th>Average Lawyer Utilization</th>
   <th>2050.1%</th>
     <tr>
    <th>Avg Client Satisfaction</th>
   <th>6.6</th>
    </tr>
</table>

<table>
  <tr>
    <th>Page Number</th>
   <th>Page 4 (Finnacial & Operational Insights) </th>
   <tr>
    <th>KPIs</th>
   <th>Values</th>
    <tr>
    <tr>
    <th>Total Internal cost</th>
   <th>€1.21bn</th>
    <tr>
    <th>Average risk Score</th>
   <th>4176%</th>
     <tr>
    <th>Avg Profit Margin</th>
   <th>460.06%</th>
   </tr>
</table>

#

## Dax Meaures
The following measures power the KPI cards, charts, and calculated logic throughout the report.

<table>
  <tr>
    <th>Measues</th>
   <th>Formula</th>
   <tr>
    <th>Total Revenue</th>
   <th>=SUM(Fact_Cases[Revenue (EUR)])</th>
    <tr>
    <th>Total Profit</th>
   <th>= SUM(Fact_Cases[Profit (EUR)])</th>
    <tr>
    <th>Total Outstanding Balance</th>
   <th> = SUM(Fact_Cases[Outstanding Balance (EUR)])</th>
    <tr>
    <th>Total Lawyer</th>
   <th>= DISTINCTCOUNT(Dim_Lawyer[Lawyer ID])</th>
     <tr>
    <th>Total Internal Cost</th>
   <th> = SUM(Fact_Cases[Internal Costs (EUR)])</th>
   <tr>
    <th>Total Client</th>
   <th>= DISTINCTCOUNT(Dim_Client[Client ID])</th>
  <tr>
    <th>Total Cases</th>
   <th>Total Cases = DISTINCTCOUNT(Dim_Case[Case ID])</th>
     <tr>
    <th>Profit Margin (%)</th>
   <th>DIVIDE([Total Profit],[Total Reveneue],0)</th>
     <tr>
    <th>Open Cases</th>
   <th>= CALCULATE([Total Cases],Dim_Case[Case Status]<> "closed")</th>
     <tr>
    <th>Closed Cases</th>
   <th> = CALCULATE([Total Cases],Dim_Case[Case Status] ="Closed")</th>
 <tr>
 <th>Average Risk Score</th>
   <th>= AVERAGE(Fact_Cases[Risk Score])</th>
    <tr>
 <th>Avg Profit Margin</th>
   <th>=  AVERAGE(Fact_Cases[Profit Margin %])</th>
     <tr>
 <th>Avg Profit Margin</th>
   <th>=  AVERAGE(Fact_Cases[Meetings])</th>
    <tr>
 <th> Lawyer Utilization % </th>
   <th>=AVERAGE(Fact_Cases[Lawyer Utilization %])</th>
        <tr>
    <th>Avg Open Days</th></th>
   <th>= AVERAGE(Fact_Cases[Days Open])</th>
      <tr>
    <th>Avg Court Apperance </th>
   <th>= AVERAGE(Fact_Cases[Court Appearances])</th>
   <tr>
    <th> Avg Client Satisfaction</th>
   <th> = AVERAGE(Fact_Cases[Client Satisfaction Score])</th>
  <tr>
    <th>Avg Billable Hours </th>
   <th>= AVERAGE(Fact_Cases[Billable Hours])</th>
 </tr>
</table>

#
## 📈 Key Features

- Interactive drill-down analysis
- Dynamic KPI cards
- Geographic office analysis
- Conditional formatting
- Executive-level dashboard design
- Cross-filtering across visuals
- Data-driven storytelling

#

## 💡Key Skills Demonstrated

- Data Cleaning with Power Query
- Data Modeling
- DAX Measure Development
- Business Intelligence
- Dashboard Design
- Data Visualization
- Business Storytelling
- Interactive Reporting
- Performance Analysis

