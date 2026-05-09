# Production Performance & Cost Analysis Dashboard

## 📊 Business Overview
In manufacturing, tracking the relationship between production volume and cost efficiency is critical for maintaining profitability. This project analyzes a production dataset to identify cost drivers, regional performance variances, and management productivity across four key product lines: Automobiles, Electronics, Furniture, and Machinery.

## 🛠️ Tech Stack & Skills
- **Excel Power Query:** Used for data cleaning and ETL (Extract, Transform, Load) processes to standardize "uncleaned" raw data.
- **Advanced Formulas:** Utilized `VLOOKUP`, `IF` statements, and date functions to create calculated fields like *Production Cost Per Unit* and *Age Grouping*.
- **Data Modeling:** Built Pivot Tables to aggregate 120+ production records into actionable summaries.
- **Data Visualization:** Designed an interactive dashboard using Slicers, Timelines, and dynamic charts for real-time filtering.

## 🚀 The Data Workflow

### 1. Data Cleaning & Transformation
The raw data required significant preparation before analysis:
- Standardized date formats for time-series consistency.
- Calculated **Production Cost Per Unit** to measure operational efficiency.
- Segmented workforce demographics into **Age Groups** to analyze potential productivity correlations.

### 2. Exploratory Data Analysis (EDA)
Key questions addressed:
- **Which product type is the most expensive to produce?** (Automobiles: $1.15M total cost).
- **Who are the top-performing managers?** (Nancy Grey: 37 tasks completed).
- **What are the seasonal trends?** (Identified a 110% increase in unit production from 2023 to 2024).

### 3. Interactive Dashboard
The final output is a dynamic dashboard that allows users to:
- Filter by **Region** (North, South, East, West).
- Drill down into specific **Product Types**.
- Monitor **Manager Performance** metrics instantly via Slicers.

## 📈 Key Findings
- **Cost Leader:** Automobiles represent the highest total expenditure, making it the primary target for cost-saving initiatives.
- **Efficiency Insight:** While Furniture has significant production volume, it maintains the highest average cost per unit ($180.44), suggesting a need for supply chain optimization.
- **Growth:** Production peaked in the first half of 2024, specifically in February and June.

## 📂 Project Structure
- **/Data**: Contains raw `Uncleaned` file.
- **/Analysis**: Pivot table summaries and calculation logic.
- **/Dashboard**: The final Excel file with the visual reporting interface.


## Dashboard Image:
<img width="1274" height="1142" alt="image" src="https://github.com/user-attachments/assets/9e727dd2-0dc3-4cef-97ce-d82e3f188851" />


