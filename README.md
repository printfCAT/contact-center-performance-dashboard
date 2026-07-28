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
