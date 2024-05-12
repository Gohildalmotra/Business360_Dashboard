
# AtliQ Hardware Data Analytics Project

## Project Overview

AtliQ Hardware is embarking on a data analytics journey using Power BI to stay ahead in the market and make data-driven decisions. This project aims to address stakeholder queries across finance, sales, marketing, and supply chain domains.

## Company Background

AtliQ Hardware, a global computer and accessories company, has expanded worldwide through retailers, direct sales, and distributors. To overcome recent losses and competitor advantages, AtliQ is embracing data analytics for informed decision-making.

I undertook this project following the Codebasics Power BI Course (https://codebasics.io/)



**Live Report Link:** [https://app.powerbi.com/view?r=eyJrIjoiZmVhZjllMmItODgwYS00N2VlLWJjYjktOTdjMzBkYTA2MWNmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9]

## Tech Stacks

- SQL
- Power BI Desktop
- Excel
- DAX language
- DAX studio (for report optimization)
- Project charter file

## Power BI Techniques Learned

- Asking critical questions before project initiation
- Creating calculated columns and measures using DAX
- Data modeling
- Using Bookmarks for visual switching
- Page navigation with buttons
- Preventing zero division errors using divide function
- Creating date tables using M language
- Dynamic titles based on filters
- Using KPI indicators
- Conditional formatting in visuals
- Data validation techniques
- Publishing reports to Power BI services
- Setting up personal gateways for data refresh
- Power BI App creation
- Collaboration and workspace management in Power BI services

## GitHub

- Uploading large files using GitHub LFS
- Tracking specific file extensions for LFS

## Business Terminology

- Gross price
- Pre-invoice deductions
- Post-invoice deductions
- Net invoice sale
- Gross Margin
- Net sales
- Net profit
- COGS (Cost of Goods Sold)
- YTD (Year to Date)
- YTG (Year to Go)
- Direct
- Retailer
- Distributors
- Consumer

## Project Kick-off

- Defining project objectives
- Measuring project success criteria
- Setting project deadlines
- Preview expectations from stakeholders
- Stakeholder hopes and concerns
- End-user expectations and dashboard usage
- Resource requirements and stakeholder inputs
- Design and view preferences
- Risk assessment and mitigation
- Data availability and engineering insights

## Dataset Understanding

## Dimension Tables

**dim_customer**

Contains details of customers across 27 distinct markets (e.g., India, USA, Spain).
Covers 75 unique customers across two platforms: Brick & Mortars (physical stores) and E-commerce (online stores like Amazon, Flipkart).
Segmented into three channels: Retailer, Direct, Distributors.

**dim_market**

Encompasses 27 markets with further breakdown into 7 sub-zones and 4 regions (APAC, EU, etc.).

**dim_product**

Categorizes products into divisions like P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S (Networking, Storage).
Includes 14 categories (e.g., Internal HDD, Keyboard) with multiple variants for each product.
## Fact Tables

**fact_forecast_monthly**

Used for advanced customer demand forecasting.
Benefits include higher customer satisfaction and reduced warehousing costs.
Denormalized for analytical purposes, replacing daily dates with monthly start dates.
Includes forecasted quantities needed by customers.

**fact_sales_monthly**

Similar to fact_forecast_monthly but contains actual sold quantities instead of forecasts.

## gdb056 Tables

**freight_cost:** Details travel and other costs per market per fiscal year.

**gross_price:** Contains gross price details with product codes.

**manufacturing_cost:** Includes manufacturing cost data with product codes and years.

**Pre_invoice_deductions and Post_invoice_deductions:** Capture pre and post-invoice deductions percentages by customer and year.

Understanding these tables is crucial for meaningful analysis and insightful reporting. Proper data modeling based on these dimensions and facts forms the foundation of robust Power BI reports.


For detailed insights and analysis, refer to the project's live report and the associated documentation.

## Importing data into PowerBi

As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

## Data Model

Data modeling is foundational to report creation, shaping the structure upon which all visuals are built. A well-designed data model is essential for optimal report performance.

In this project, we adhere to best practices in data modeling, emphasizing the Snowflake data modeling method. This approach ensures data integrity, scalability, and efficient query performance, resulting in insightful and accurate Power BI reports.

![360 data model ](https://github.com/Gohildalmotra/Business360_Dashboard/assets/123579887/3414be80-1146-43fc-9e09-5f4e1c1d8655)

## Dashboard designing

## Home View

The Home view provides access to various sections via dedicated buttons, allowing users to navigate to specific pages seamlessly.

- Info
- Finance View
- Sales View
- Marketing View
- Supply Chain View
- Executive View
- Support

Each button leads to a focused area, ensuring efficient navigation and access to relevant information based on user requirements.

## Info

![360 info ](https://github.com/Gohildalmotra/Business360_Dashboard/assets/123579887/11334788-f612-41d5-9f51-c2d95fb29f43)

## Finance View

![360 Finance](https://github.com/Gohildalmotra/Business360_Dashboard/assets/123579887/c3f6180f-ce99-441d-9165-0ca1b642c8df)

## Sales View

![360 sales](https://github.com/Gohildalmotra/Business360_Dashboard/assets/123579887/a4cb7004-4e27-4626-923f-c18609cac647)

## Marketing View

![360 Marketing](https://github.com/Gohildalmotra/Business360_Dashboard/assets/123579887/74668fc6-9fe1-42fe-8883-6adbe542c2ab)

## Supply Chain View

![360 supply chain](https://github.com/Gohildalmotra/Business360_Dashboard/assets/123579887/1352214f-857b-4271-a6e3-0bd600a090e1)

## Executive View

![360 executive ](https://github.com/Gohildalmotra/Business360_Dashboard/assets/123579887/1d9ec719-cebf-49c8-a76a-4751e62d136f)

you can find the full report file here : Report
