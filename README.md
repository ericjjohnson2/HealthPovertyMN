# Public Health Data Analysis: Poverty and Heart Disease Rates

## Introduction

This project investigates the potential relationship between poverty rates and heart attack prevalence in Minnesota counties. Heart disease is a leading cause of death in the United States, and poverty is a known risk factor for poor health outcomes. We aimed to explore whether poverty rates correlate with higher heart attack rates across Minnesota counties.

## Motivation

Heart disease's impact on communities and its potential link to socio-economic factors necessitate a deeper investigation. Understanding this relationship can help tailor public health interventions and policies to address heart disease more effectively, particularly in underprivileged areas.

## Data Acquisition and Cleaning

- **Poverty Data:** Gathered by county and year using the Census API, including demographic details (race, gender, age). 
- **Heart Attack Data:** Obtained from the Centers for Disease Control and Prevention (CDC), focusing on heart attack death data.
- **Cleaning Process:** Due to limitations in the homogeneity of health data, we focused on overall poverty rates and county types based on Office of Management and Budget (OMB) definitions.

## Analysis and Results

Our analysis aimed to identify any correlation between poverty rates and heart disease prevalence. Despite an R-squared value of 0.0311, indicating a low correlation, this result does not negate the possibility of a relationship. The analysis was hindered by time constraints and data distribution challenges, as highlighted by the Shapiro-Wilk test indicating non-normality in heart attack data distribution.

## Limitations

- **Data Representativeness:** The focus on heart attacks might limit insights compared to analyzing broader health conditions.
- **Data Measurement:** Variations in poverty and health statistics definitions could affect outcomes. A per capita basis might be more appropriate for analyzing smaller counties.
- **Geographic Scope:** Limiting the study to Minnesota may affect the generalizability of findings due to regional variations and a smaller dataset.
- **Statistical Expertise:** Further analysis could benefit from collaboration with statistical experts, particularly in interpreting r-squared and p-values.

## Conclusion

The initial analysis did not find a strong correlation between poverty rates and heart attack rates in Minnesota. However, the absence of statistically significant results does not imply a lack of relationship. Further research, possibly with contributions from public health professionals, could provide a more comprehensive understanding of the link between socio-economic status, environmental factors, and health outcomes.

## Additional Notes

- Importing data via the Census API may take an hour or more due to the volume of the dataset.

## Contributors:
Eric Johnson, Paul Moses, Waynei Mebrahtu, Mitchell Lor, and Lucinda Hodgson




