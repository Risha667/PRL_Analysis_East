PRL Project: Expanding Business East of the Mississippi
Table of Contents
Overview
Features
Technologies Used
Datasets
Data Cleaning and Preparation
Installation and Setup
Visualizations and Dashboards
Results and Insights
Recommendations

--------------------------------------------------------------------------------
1. Overview
This project analyzes healthcare organizations and physician data 
east of the Mississippi River to provide actionable insights for 
Physician Resources Limited (PRL) to expand its services. By identifying 
high-revenue organizations and specialties with significant physician 
presence, PRL can target lucrative markets for partnerships and growth.

--------------------------------------------------------------------------------
2. Features

Physician Analysis:
-Distribution of physicians by state, ownership, and specialties.
-Entity types: parent, subsidiary, and independent.

Company Analysis:
-Revenue, assets, and employment trends by state and industry.
-Insights into high-revenue companies and regions.

Dynamic Dashboards:
-Comprehensive visualizations created in R Markdown.

--------------------------------------------------------------------------------
3. Technologies Used
#R Studio: Data cleaning, transformation, and visualization.
#R Markdown: Dynamic report generation.
#PowerPoint: For presentation of key findings.

--------------------------------------------------------------------------------
4. Datasets
PRL East Companies:
Fields: revenue, assets, employee count, ownership type, state.

PRL East Physicians:
Fields: specialties, state-wise physician counts, SIC codes, and ownership types.
PRL Industry and Specialties:
Includes SIC-8 codes and categorization for filtering industries and specialties.

--------------------------------------------------------------------------------
5. Data Cleaning and Preparation
Steps Taken

--Filtering Data:
Excluded areas such as dentistry, dermatology, ophthalmology, long-term care, 
and rehabilitation facilities.Retained relevant industries and specialties 
using SIC-8 codes.

--Handling Missing Values:
Imputed missing values in critical fields such as revenue and employment where 
necessary.


--Categorization:
Grouped physicians by specialties and industries.Categorized organizations into 
ownership types: nonprofit, private, public, partnerships.

--Data Transformation:
Calculated percentages for ownership distributions and specialty concentration.
Summarized state-wise metrics for visualization.

--Validation:
Verified data consistency and alignment with project objectives.

--------------------------------------------------------------------------------
6. Installation and Setup
Pre-Requisites
Install R Studio and R.
Install required R libraries:
-tidyverse, ggplot2, dplyr, knitr, rmarkdown.

Steps
Download the datasets 
-PRL East Companies Final 2024-03.csv
-PRL East Physicians Final 2024-03.csv) to your local computer.
Open the R Markdown file (PRL Project File.Rmd) in R Studio.
Ensure the datasets are saved in the correct file path as referenced in the R Markdown file.
Run the file directly in R Studio to generate dynamic visualizations and insights.

--------------------------------------------------------------------------------
7. Visualizations and Dashboards

## 1. Physician Distribution Analysis
Focus: Distribution of physicians by state, ownership type, and specialties.
Highlights:
New York leads in physician count, primarily in nonprofit hospitals.

## 2. Revenue and Asset Analysis
Focus: Insights into high-revenue healthcare companies.
Highlights:
HCA Healthcare leads with $51.3 billion in revenue.

## 3. Specialty Analysis
Focus: Concentration of physicians in high-demand specialties.
Highlights:
General Medical and Surgical Hospitals employ the highest number of physicians.

--------------------------------------------------------------------------------
8. Results and Insights
Key Findings:

Physician Insights:
-47% of physicians work in hospitals; nonprofits dominate ownership.
-Tennessee and Florida follow New York in physician count.

Company Insights:
-HCA Healthcare leads in revenue and assets.
-New York, Pennsylvania, and Tennessee are key markets.

----------------------------------------------------------------------------------
9. Recommendations

Target High-Revenue Areas:
Focus on New York and Pennsylvania for maximum ROI.

Engage with Nonprofits:
Leverage relationships with nonprofit organizations dominating the market.

Specialty Targeting:
Concentrate on General Medical and Surgical Hospitals and Mental Health Clinics.

Geographic Focus:
Expand partnerships in Tennessee and Florida.
