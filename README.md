# Life Expectancy Analysis in Southeast Asia (2015) 🌏

## Project Overview
This repository contains a data mining project focused on analyzing the factors affecting 
**Life Expectancy (LE)** in Southeast Asian countries. By applying **Linear Regression**, 
this study aims to quantify the impact of socio-economic and health variables on the average 
age of survival in the region during the year 2015.

## Objectives
1.  Identify key socio-economic factors influencing life expectancy.
2.  Analyze the relationship between GDP, schooling, and health indicators with life expectancy.
3.  Measure the significance of each variable using a Linear Regression model.
4.  Demonstrate the application of data mining workflows using **RapidMiner**.

## Dataset
The data is compiled from secondary sources:
* **Kaggle:** Global life expectancy and health factors.
* **World Bank:** GDP per capita and educational statistics.

### Variables Analyzed:
| Variable | Description | Unit |
| :--- | :--- | :--- |
| **Life Expectancy** | Life expectancy at birth (Target Variable) | Years |
| **Hepatitis B** | Hepatitis B immunization coverage among children | % |
| **GDP** | Gross Domestic Product per capita | USD |
| **Schooling** | Average years of schooling | Years |
| **HIV/AIDS** | Prevalence of HIV/AIDS | % of population |

## Methodology
The project follows a standard Data Mining pipeline:
1.  **Selection:** Filtering the global dataset for Southeast Asian countries for the year 2015.
2.  **Preprocessing:** Handling missing values and ensuring data quality in .csv format.
3.  **Processing:** Applying the Linear Regression algorithm within RapidMiner.
4.  **Evaluation:** Measuring model performance using Coefficient of Determination ($R^2$) and Root Mean Squared Error (RMSE).

## Key Findings
* **Model Accuracy:** The regression model achieved an **R-Squared ($R^2$) of 0.860**, indicating that the independent variables explain 86% of the variations in life expectancy.
* **Error Rate:** The **RMSE is 2.004**, suggesting a prediction error margin of approximately 2 years.
* **Primary Drivers:** Economic indicators (GDP) and education (Schooling) were found to be the most significant contributors to higher life expectancy in the region.

## Tools Used
* **RapidMiner:** For data modeling and evaluation.
* **Excel:** For initial data cleaning and formatting.

## Conclusion
The application of data mining proves that socio-economic factors are powerful predictors of public health. This model provides a reliable framework for policymakers to identify which sectors (Education, Economy, or Health) require the most investment to improve the quality of life in Southeast Asia.
