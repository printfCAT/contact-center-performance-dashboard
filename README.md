# contact-center-performance-dashboard
# Overview
This project demonstrates the development of an end-to-end Business Intelligence solution for monitoring and analyzing contact center performance using Microsoft Power BI. The dashboard transforms raw operational data into interactive visual reports that support data-driven decision-making for contact center management.

The solution follows a modern Business Intelligence workflow by implementing:
* ETL processes using Power Query (M)
* A Star Schema data model
* Advanced DAX measures and calculated columns
* Interactive Power BI dashboards
* KPI reporting for operational performance monitoring

The dashboard was developed as part of my preparation for Management Information Systems (MIS) Analyst and Business Intelligence Analyst roles.

# Business Problem
Contact center operations generate large volumes of operational data every day. While this data contains valuable insights, it is often spread across multiple tables and difficult to interpret without effective reporting.

This project addresses that challenge by transforming raw operational data into meaningful dashboards that allow supervisors and managers to:

* Monitor operational performance
* Track key contact center KPIs
* Identify performance trends
* Compare departments and supervisors
* Support operational and strategic decision-making

# Objectives
This project aims to:

* Build a scalable Power BI data model using a Star Schema.
* Clean and transform operational datasets using Power Query.
* Develop reusable DAX measures for business KPIs.
* Produce interactive dashboards that provide operational insights.
* Demonstrate practical Business Intelligence and data modelling skills.

# Tools & Technologies
| Tool | Purpose |
| ---- | ------- |
| Microsoft Power BI | Dashboard development |
| Power Query (M) | ETL and data transformation |
| DAX	| KPI calculations |
| Excel	| Source data |
| SQL Concepts | Data modelling and analytical thinking |
| GitHub | Version control and portfolio |

# Data Model
The project uses a Star Schema, a common data warehousing design that improves reporting performance and simplifies analytical queries.
<img width="1920" height="1080" alt="star-schema" src="[https://github.com/user-attachments/assets/10a2df80-77c5-48df-839d-2b3f42496e67](https://github.com/printfCAT/contact-center-performance-dashboard/blob/main/project-screenshots/star-schema.png)" />

## Fact Table
FactCalls

Contains transactional call data including:

* Call ID
* Agent
* Date
* Handle Time
* First Call Resolution
* Customer Satisfaction
* SLA Status
* Department
* Supervisor

## Dimension Tables

* Agents
* Departments
* Supervisors
* Date

This design minimizes redundancy while improving report performance and scalability.

# ETL Process

Power Query (M) was used to prepare the dataset before loading it into Power BI.

The ETL process included:

* Importing source data
* Removing duplicate records
* Handling missing values
* Correcting data types
* Standardizing text formatting
* Creating calculated columns
* Building relationships between tables
* Preparing clean datasets for reporting

This ensured consistency and improved overall data quality.

# Key Performance Indicators (KPIs)

The dashboard analyzes several common contact center KPIs including:

* Average Handle Time (AHT)
* First Call Resolution (FCR)
* Customer Satisfaction (CSAT)
* Service Level Agreement (SLA)
* Quality Score (QA)
* Total Calls
* High AHT Calls
* Department Performance
* Agent Performance

These metrics provide operational visibility and help identify opportunities for improvement.
<img width="1920" height="1080" alt="dashboard" src="[https://github.com/user-attachments/assets/10a2df80-77c5-48df-839d-2b3f42496e67](https://github.com/printfCAT/contact-center-performance-dashboard/blob/main/project-screenshots/dashboard.png)" />

# DAX Measures

The project includes several reusable DAX measures, such as:

* Average AHT
* Average CSAT
* FCR %
* SLA %
* Total Calls
* High AHT Calls
* Month-to-Date (MTD) AHT
* Month-to-Date (MTD) FCR
* Percentage of Total Calls

These measures demonstrate the use of filter context, CALCULATE(), DIVIDE(), aggregation functions, and time intelligence.

# Dashboard Features

The dashboard provides:

* Executive KPI summary cards
* Department performance comparison
* Supervisor performance analysis
* Agent-level drill-down
* Trend analysis over time
* Interactive slicers
* Conditional formatting
* Dynamic filtering
* Cross-report interactions

The dashboards are designed to enable users to quickly identify operational trends and performance issues.

# Data Quality

Data quality was an important consideration throughout the project.

Validation activities included:

* Removing duplicate records
* Correcting inconsistent text values
* Validating data types
* Checking relationships between tables
* Ensuring accurate KPI calculations
* Verifying DAX measure outputs
* Cleaning incomplete records before reporting

Maintaining clean data improved report reliability and decision-making.

# Business Insights

The dashboard makes it possible to identify insights such as:

* Departments with consistently higher Average Handle Time.
* Teams with declining Customer Satisfaction.
* Supervisors achieving the strongest overall KPI performance.
* Departments requiring coaching interventions.
* Operational trends across different reporting periods.
* Opportunities for process improvement.

These insights support evidence-based operational decisions.

# Future Improvements

Potential future enhancements include:

* SQL Server integration
* Azure Data Factory ETL pipelines
* Automated dataset refresh
* Row-Level Security (RLS)
* Paginated reports
* Power BI Service deployment
* Python integration for statistical analysis
* Real-time dashboard updates
* Larger production datasets

# Skills Demonstrated

This project demonstrates practical experience with:

* Business Intelligence
* Power BI Development
* Dashboard Design
* Data Visualization
* Power Query (M)
* DAX
* Data Modelling
* Star Schema Design
* ETL Processes
* KPI Reporting
* Data Cleaning
* Data Validation
* Contact Centre Analytics
* Analytical Problem Solving

# About Me

I developed this project while preparing for Management Information Systems (MIS) Analyst and Business Intelligence roles. My objective was to build a solution that mirrors the reporting requirements of a modern contact center by applying industry-standard Business Intelligence techniques using Microsoft Power BI.

I welcome feedback and suggestions for improving the project.
