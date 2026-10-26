# India CPI Inflation Analysis | Excel Data Analytics Project

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-0F6CBD?style=for-the-badge&logo=microsoftpowerquery&logoColor=white)
![Data Cleaning](https://img.shields.io/badge/Data_Cleaning-FF9800?style=for-the-badge&logoColor=white)
![Data Transformation](https://img.shields.io/badge/Data_Transformation-8E44AD?style=for-the-badge&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/PivotTables-16A085?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Exploratory Data Analysis](https://img.shields.io/badge/Exploratory_Data_Analysis-2980B9?style=for-the-badge&logoColor=white)
![Inflation Analysis](https://img.shields.io/badge/CPI_Inflation_Analysis-E74C3C?style=for-the-badge&logoColor=white)
![Trend Analysis](https://img.shields.io/badge/Trend_Analysis-3498DB?style=for-the-badge&logoColor=white)
![Correlation Analysis](https://img.shields.io/badge/Correlation_Analysis-6C3483?style=for-the-badge&logoColor=white)
![Time Series Analysis](https://img.shields.io/badge/Time_Series_Analysis-117864?style=for-the-badge&logoColor=white)


##  Project Overview

This project explores India's Consumer Price Index (CPI) data through category-wise, sector-wise, monthly, and year-wise analysis using Microsoft Excel.

The project focuses on understanding inflation-related trends across major consumption categories, comparing rural and urban price movements, examining selected categories before and after COVID-19, and investigating the relationship between fuel and other essential categories.

The analysis presented in this repository covers **Worksheet 4 through Worksheet 14** of the Excel workbook, including broader category analysis, food inflation, COVID-period comparisons, fuel comparisons, and correlation analysis.

## Project Objectives

- Analyze the distribution of CPI observations across broader consumption categories.
- Compare general CPI index trends across Rural, Urban, and Rural+Urban sectors.
- Identify monthly movements in important food categories.
- Compare food-category CPI index values between 2022 and 2023.
- Examine changes in food and beverages, health, and household goods and services around the COVID-19 period.
- Compare fuel and light with transport, food and beverages, non-alcoholic beverages, clothing and footwear, and cereals.
- Measure relationships between selected category-level monthly percentage changes using correlation analysis.

## Tools and Techniques

- **Microsoft Excel** — Data analysis, PivotTables, formulas, and summaries.
- **Power Query** — Data transformation and preparation.
- **PivotTables** — Category-wise, sector-wise, and time-based comparisons.
- **Excel formulas** — Percentage-change calculations and correlation using `CORREL()`.
- **Data interpretation** — Identifying trends and comparing CPI movements.

##  Worksheet-Wise Project Documentation

### 1. Broader Categories Wise Inflation

**Purpose:** Examine how the observations in the unpivoted dataset are distributed across broader consumption categories.

The worksheet summarizes categories such as Food, Clothing, Education, Fuel and Light, Health, Housing, Luxury, and Transport and Communication.

<img width="912" height="512" alt="image" src="https://github.com/user-attachments/assets/dce1207e-6ccc-47ab-bdbe-d565d989dad4" />


**Key observation:** Food accounts for approximately **44.46%** of the classified observations, making it the largest category in this worksheet. Luxury accounts for approximately 14.82%, while Clothing accounts for approximately 11.12%.

*Note: These percentages represent the distribution of classified observations, not the inflation rate of each category.*

### 2. Year-on-Year Inflation by Sector

**Purpose:** Compare annual average General Index values across Rural, Urban, and Rural+Urban sectors from 2016 to 2023.

The worksheet includes sector-wise averages and year-over-year percentage-change calculations.


<img width="780" height="480" alt="image" src="https://github.com/user-attachments/assets/d4001dc9-0913-43fb-a981-99bd6fa486ae" />


**Key observations:**
- The average General Index increased across all three sectors over the displayed period.
- Rural index values were generally higher than urban index values.
- The combined Rural+Urban series provides an overall comparison of the two sectors.

This analysis helps identify long-term price-level movements and differences between rural and urban areas.

### 3. Month-Wise Food Categories Inflation

**Purpose:** Examine monthly CPI index movements for four food categories: Milk and Products, Vegetables, Pulses and Products, and Fruits.

The worksheet compares monthly values across 2022 and the available months of 2023, with percentage-change calculations for successive observations.


<img width="877" height="456" alt="image" src="https://github.com/user-attachments/assets/e65bfc3d-6904-4d02-9503-4a580efef477" />


**Key observations:**
- Vegetable index values fluctuated substantially during 2022, reaching an average of approximately 204.37 in October before declining toward the end of the year.
- Milk and products showed a generally increasing trend across the displayed months.
- Fruits and pulses followed different monthly patterns, highlighting the importance of analyzing food categories separately.

This analysis helps identify seasonal fluctuations and changing food-price patterns.

### 4. Absolute Inflation in Food Categories

**Purpose:** Compare average CPI index values for major food categories across Rural, Urban, and Rural+Urban sectors in 2022 and 2023.

The worksheet includes cereals and products, eggs, fruits, meat and fish, milk and products, oils and fats, prepared meals, pulses, spices, sugar and confectionery, vegetables, and food and beverages.


<img width="1065" height="462" alt="image" src="https://github.com/user-attachments/assets/e7c9f433-07c4-4b94-8dd6-5e2813ea697c" />


**Key observations:**
- Cereals and products recorded higher average index values in 2023 than in 2022 across all three sectors.
- Spices also showed a notable increase in average index values.
- Oils and fats and vegetables recorded lower average index values in 2023 than in 2022 in the displayed comparison.
- The direction and magnitude of changes varied by food category and sector.

These comparisons help identify which food categories experienced rising or declining average price-index levels.

*Note: The worksheet compares CPI index values. Percentage changes in these values should be calculated separately before describing them as inflation rates.*

### 5. Pre- and Post-COVID Analysis

**Purpose:** Compare annual average CPI index values for three categories:

- Food and Beverages
- Health
- Household Goods and Services

The worksheet covers annual observations from 2013 through 2023 and provides a historical perspective on price movements before and after the pandemic period.


<img width="940" height="482" alt="image" src="https://github.com/user-attachments/assets/71e5581b-2ea7-42e8-ab35-fb73db29e3c2" />



**Research focus:**
- How did the selected category indices change before COVID-19?
- How did the trends develop during the pandemic period?
- Did food, health, and household-related categories show different patterns afterward?

This comparison provides context for understanding inflation-related changes around COVID-19. It does not independently establish that the pandemic caused the observed movements.

## 6.1 Fuel vs. Non-Alcoholic Beverages

**Purpose:** Compare the monthly CPI movements of Fuel and Light with Non-Alcoholic Beverages.

The worksheet examines the two series and calculates percentage changes to assess whether their short-term movements are associated.


<img width="757" height="432" alt="image" src="https://github.com/user-attachments/assets/01cd0096-c80e-4255-8905-4b7fe1e53abb" />


This provides an additional category-level comparison of fuel and consumer beverage prices.


## 6.2 Fuel vs. Cereals and Products

**Purpose:** Analyze the relationship between Fuel and Light and Cereals and Products.

The worksheet compares monthly average CPI index values and calculates successive percentage changes for both categories.


<img width="807" height="497" alt="image" src="https://github.com/user-attachments/assets/e08b77d1-6bca-4103-b6ac-e66dd9798755" />



This comparison is particularly useful for exploring the relationship between energy-related price movements and a major food category.


### 11. Correlation Analysis

**Purpose:** Summarize the correlation coefficients calculated for fuel and five selected consumption categories.

The worksheet reports the following results:

| Category Comparison | Correlation |
|---|---:|
| Fuel vs. Non-Alcoholic Beverages | +0.689 |
| Fuel vs. Transport | +0.662 |
| Fuel vs. Clothing and Footwear | +0.423 |
| Fuel vs. Food and Beverages | -0.199 |
| Fuel vs. Cereals and Products | -0.239 |


<img width="622" height="405" alt="image" src="https://github.com/user-attachments/assets/018dec02-ab9e-4860-a9b8-122b279c8c44" />


**Interpretation:**

- **Non-Alcoholic Beverages (+0.689):** A moderately strong positive linear relationship with fuel percentage changes.
- **Transport (+0.662):** A moderate-to-strong positive relationship with fuel percentage changes.
- **Clothing and Footwear (+0.423):** A moderate positive relationship.
- **Food and Beverages (-0.199):** A weak negative relationship.
- **Cereals and Products (-0.239):** A weak negative relationship.

The results suggest that fuel's monthly percentage changes were more closely associated with those of transport and non-alcoholic beverages than with food and cereals in the selected observations.

**Important:** Correlation measures association, not causation. These results depend on the observation period, the calculations, and the data ranges used in the workbook.

## 📈 Key Insights

1. **Food dominates the category distribution:** Food represents approximately 44.46% of classified observations in the broader-category worksheet.
2. **Rural and urban indices differ:** Rural General Index averages were generally higher than urban averages in the displayed annual comparison.
3. **Food categories behave differently:** Vegetables, spices, cereals, milk, and oils and fats show distinct patterns, so food inflation should not be treated as a single uniform movement.
4. **COVID-period analysis adds context:** Comparing food, health, and household-related categories helps examine how price-index trends evolved around the pandemic.
5. **Fuel relationships vary by category:** The correlation results show positive associations with transport and non-alcoholic beverages but weak negative associations with food and cereals.
6. **Index levels and inflation rates are different:** An increase in the CPI index indicates a higher measured price level relative to the index base. The percentage change over time is needed to quantify inflation over that period.

## How to Explore the Project

1. Download or clone this repository.
2. Open `CPI Inflation Project.xlsx` in Microsoft Excel.
3. Start with **Worksheet 4: Broader Categories wise Inflati**.
4. Explore Worksheets 5–8 for sector-wise, food-category, and COVID-period comparisons.
5. Review Worksheets 9–13 for fuel-related comparisons.
6. Open Worksheet 14, **Correlation**, to review the summary of correlation coefficients.
7. Inspect the PivotTables, formulas, and source ranges to understand how the results were calculated.

## Dataset Information

- **Country:** India
- **Time period:** The workbook contains CPI data from 2013 to 2023; individual analysis worksheets use different subsets of this period.
- **Frequency:** Monthly source observations, with annual averages used in selected summaries.
- **Sectors:** Rural, Urban, and Rural+Urban.
- **Measures:** CPI index values, calculated percentage changes, and correlation coefficients.

**Data source:** Add the official dataset source and reference link here before publishing. The source URL is not identified in the workbook.

## Limitations

- Some worksheets cover selected years or months rather than the full dataset.
- CPI index values should not be interpreted directly as percentage inflation rates.
- Pre- and post-COVID comparisons show observed patterns but do not prove causation.
- Correlation coefficients depend on the selected observations and formulas.
- Results should be interpreted in the context of the CPI base period and the source data's methodology.

## Skills Demonstrated

- Microsoft Excel
- Power Query
- PivotTable analysis
- CPI and inflation trend analysis
- Sector-wise and category-wise comparisons
- Percentage-change calculations
- Correlation analysis
- Data interpretation and analytical documentation

## Author

**Aastha Dubey**

Aspiring Data Analyst | Excel | Power Query | Data Analytics

- GitHub: https://github.com/sonaliwindow300-sudo
- Email Id- sonaliwindow300@gmail.com
- LinkedIn: https://www.linkedin.com/in/aastha-dubey-882609300?utm_source=share_via&utm_content=profile&utm_medium=member_android
---

⭐ If you find this project useful, consider starring the repository!
