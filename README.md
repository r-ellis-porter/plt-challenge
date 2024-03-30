# Pymaceuticals Inc. Anti-Cancer Medication Study

## Overview

Welcome to the Pymaceuticals Inc. Anti-Cancer Medication Study repository! Pymaceuticals, Inc. is a pharmaceutical company specializing in anti-cancer medications. In a recent animal study, 249 mice with squamous cell carcinoma (SCC) tumors were treated with various drug regimens to compare the efficacy of Pymaceuticals’ drug of interest, Capomulin, against other treatments. As a senior data analyst, my task was to analyze the study data and provide comprehensive tables and figures for the technical report of the clinical study.

## Important Findings

- **Correlation between Mouse Weight and Tumor Volume**: There is a strong positive correlation (r > 0.7) between mouse weight and the average tumor volume for mice on the Capomulin regimen.
- **Tumor Volume Distribution**: The distribution of final tumor volumes for mice treated with Capomulin and Ramicane is lower compared to Infubinol and Ceftamin regimens.

## Summary

This project entails various data analysis tasks including data preparation, summary statistics generation, visualization creation, and correlation/regression analysis. The key tasks include:

- **Data Preparation**: Merging datasets, identifying and handling duplicate entries.
- **Summary Statistics**: Calculating mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.
- **Visualization**: Creating bar charts and pie charts to visualize data distribution and gender distribution among mice.
- **Quartiles, Outliers, and Boxplots**: Calculating quartiles, identifying potential outliers, and generating boxplots to visualize tumor volume distribution.
- **Line and Scatter Plots**: Plotting tumor volume vs. time point for a single mouse treated with Capomulin and creating a scatter plot of mouse weight vs. average observed tumor volume for the Capomulin regimen.
- **Correlation and Regression**: Calculating the correlation coefficient between mouse weight and average observed tumor volume, and fitting a linear regression model.

## Technical Details

### Data Preparation
- Merged mouse metadata and study results datasets into a single DataFrame.
- Handled duplicate entries and created a clean DataFrame for analysis.

### Summary Statistics
- Calculated mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen using both groupby and aggregation methods.
- Presented summary statistics in tabular format.

### Visualization
- Generated bar charts to display the total number of observed mouse timepoints for each drug regimen.
- Created pie charts to visualize the distribution of female versus male mice in the study.

### Quartiles, Outliers, and Boxplots
- Calculated quartiles and identified potential outliers for four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Plotted boxplots to visualize the distribution of final tumor volume for each treatment group, highlighting potential outliers.

### Line and Scatter Plots
- Generated a line plot to visualize tumor volume vs. time point for a single mouse treated with Capomulin.
- Created a scatter plot to display mouse weight vs. average observed tumor volume for the entire Capomulin regimen.

### Correlation and Regression
- Calculated the correlation coefficient between mouse weight and average observed tumor volume for the Capomulin regimen.
- Fitted a linear regression model and plotted it on top of the scatter plot to visualize the relationship between mouse weight and tumor volume.

## Conclusion

This analysis provides valuable insights into the effectiveness of different drug regimens in treating squamous cell carcinoma tumors in mice. The correlation and regression analysis reveal a strong positive relationship between mouse weight and tumor volume for mice treated with Capomulin. Additionally, the visualization of tumor volume distribution and outliers helps in understanding the efficacy of different treatment regimens. These findings are crucial for informing further research and development efforts in anti-cancer medication.

For detailed code implementation and analysis, please refer to the provided Python script.
