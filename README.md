# Greater Manchester Domestic Energy Performance Analyzer

## Introduction
The **Greater Manchester Domestic Energy Performance Analyzer** is a Power BI dashboard designed to analyze and visualize Energy Performance Certificate (EPC) data for the Greater Manchester region, covering the years 2013 to 2023. EPCs provide essential information about the energy efficiency of buildings and help stakeholders in the energy sector make informed decisions. This project aims to explore trends in energy performance, such as energy costs, CO2 emissions, and energy efficiency ratings for various property types, and present these insights through an interactive and user-friendly Power BI dashboard.

## Purpose
The purpose of this project is to design an effective Power BI dashboard that investigates energy performance trends and helps stakeholders make informed decisions. It includes:
- Data cleaning, transformation, and visualization.
- Interactive and customizable features for detailed analysis.
- Insights into energy consumption, emissions, and potential areas for improvement in energy efficiency.

## Dataset

The dataset used in this project is from the **Energy Performance Certificate (EPC)** database provided by [Open Data Communities](https://epc.opendatacommunities.org/downloads/domestic#local-authority). The data includes energy performance details for residential properties in Greater Manchester, with entries from 2006 to 2024. The dataset has 92 columns and 300,888 rows, capturing key metrics like:
- Energy efficiency ratings
- CO2 emissions
- Energy costs (heating, lighting, water)
- Property types and locations

### Data Cleaning Process
1. **Data Import**: The dataset was imported into SQL Server Management Studio (SSMS) and stored in a database called `01_Greater_Manchester_Domestic_EPA`.
2. **Cleaning Steps**:
   - Removed irrelevant columns.
   - Handled missing values and duplicates.
   - Standardized data formats and ensured consistency.
3. **Preparation**: The cleaned dataset was made ready for analysis and visualization in Power BI, ensuring accuracy and consistency.

## Dashboard Design & Implementation

### Dashboard Pages

1. **Page 1: Overview of Energy Performance (2013-2023)**  
   This page presents an overview of energy performance in Greater Manchester, showcasing key metrics like EPC rating, CO2 emissions, energy costs, and property types. Users can filter and query data to view trends in energy efficiency and potential improvements.

2. **Page 2: Energy Efficiency Analysis**
   - **Bar Graph**: Displays the count of current energy efficiency ratings by property type.
   - **Line Graph**: Compares the average current and potential energy efficiency over time.
   - **Gauge Charts**: Represent current and potential energy efficiency on a scale from 0 to 100.
   - **Key Insight**: Energy efficiency has been steadily improving, with room for further improvements in many properties.

3. **Page 3: CO2 Emissions Visualization**
   - **Maps**: Show CO2 emissions by constituency.
   - **Line Charts**: Represent trends in CO2 emissions over time.
   - **Key Insight**: Some constituencies have higher CO2 emissions, indicating areas that need targeted environmental efforts.

4. **Page 4: Energy Consumption Analysis**
   - **Maps**: Display energy consumption across different constituencies.
   - **Bar and Pie Charts**: Show breakdowns of energy consumption by property type and fuel source.
   - **Key Insight**: Mains gas is the most commonly used fuel source for heating, but there is potential for energy savings.

5. **Page 5: Energy Cost Analysis**
   - **Charts**: Display the cost of heating, lighting, and hot water by fuel source.
   - **Line Chart**: Tracks the increase in heating costs over time.
   - **Key Insight**: Heating costs have increased over the years, with mains gas being the most expensive fuel type.

6. **Page 6: Property-Specific Energy Performance**
   - **Charts**: Display energy efficiency ratings, property types, and environmental impact.
   - **Trend Analysis**: Shows the gap between potential and actual energy efficiency, suggesting areas for improvement.

## Conclusion
The **Greater Manchester Domestic Energy Performance Analyzer** dashboard provides a comprehensive view of energy performance in the region. The analysis highlights trends in energy efficiency, CO2 emissions, and energy consumption, offering actionable insights for stakeholders in the energy sector. The dashboard allows for easy comparison between property types, energy ratings, and constituencies, helping identify areas where energy efficiency can be improved.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/greater-manchester-domestic-energy-performance-analyzer.git
