## Project Overview

This project presents a detailed analysis of production data using Microsoft Excel.
The objective is to evaluate production efficiency, cost management, and team performance through calculated fields, pivot tables, and an interactive dashboard.

The analysis helps management understand how production varies by product type, manager, and time period, as well as how costs behave across different product lines.

## Dataset Description

The dataset contains production-related information, including details about managers, products, production units, costs, and time periods.

Key Columns:

Product Type / Product Line – Category of the manufactured item

Manager – Person responsible for the production tasks

Year / Month – Time period of production

Total Cost – Total expenditure on production

Units Produced – Total quantity manufactured

Task ID / Task Name – Identification of each production task

## Calculated Fields

Age Group – Derived using a Nested IF formula based on employee or equipment age brackets.

=IF(Age<25,"Young",IF(Age<=40,"Mid Age","Senior"))

Production Cost per Unit – Calculated to measure efficiency using:

=Total Cost / Units Produced

These calculated fields enable cost comparison across departments and help in workforce segmentation for productivity analysis.

## Pivot Table Analysis
### Pivot 1: Total Cost by Product Type

Rows: Product Type

Values: Sum of Total Cost

Insight: Identifies which product types are the most cost-intensive in production.

### Pivot 2: Number of Tasks by Manager

Rows: Manager

Values: Count of Tasks

Insight: Helps monitor workload distribution and managerial efficiency.

### Pivot 3: Units Produced by Year and Month

Rows: Year, Month

Values: Sum of Units Produced

Insight: Tracks production trends over time, highlighting seasonality or performance fluctuations.

### Pivot 4: Average Production Cost per Unit by Product Line

Rows: Product Line

Values: Average of Production Cost per Unit

Insight: Evaluates cost-effectiveness and identifies high or low-cost product lines.

## Dashboard Overview

An interactive Excel Dashboard has been created to visualize:

Yearly and monthly production performance

Cost efficiency by product type and line

Managerial task distribution

Trends and KPIs derived from calculated fields

## Features:

Dynamic slicers for filtering by product type, manager, and year

Automatically updating charts and KPIs

User-friendly layout for management review.



