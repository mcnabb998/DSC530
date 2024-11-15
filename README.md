# Bear Incident Analysis Project

### Overview
This project explores the factors involved in bear incidents across North America, focusing on demographic and temporal patterns to determine if age and other variables influence the type of incident (wild vs. captive bear encounters). The analysis aims to test the hypothesis that the age of individuals involved in bear incidents differs based on whether the bear was wild or captive.

### Contents
This repository contains the following files:
- **`Bear_Incident_Analysis_Presentation.pptx`**: PowerPoint presentation summarizing the project’s goals, methodology, key findings, and conclusions.
- **`bear_incidents_dataset.csv`**: The dataset of bear incidents in North America, including variables such as Age, Year, Type (wild or captive), Type of Bear, and incident outcomes.
- **`Bear_Incident_Analysis_Notebook.ipynb`**: Jupyter notebook that contains the full exploratory data analysis (EDA), statistical tests, and logistic regression analysis conducted for this project.

### Project Hypothesis
The hypothesis tested in this project is:
> "The age of individuals involved in bear incidents differs based on whether the bear was wild or captive."

### Dataset Details
The dataset includes variables like:
- **Age**: Age of the individual involved in the incident.
- **Year**: Year the incident occurred.
- **Type**: Type of bear encounter (Wild or Captive).
- **Type of Bear**: Species of bear involved in the incident.
- **Only one killed**: Indicator of whether only one person was killed in the incident.

This dataset was cleaned and prepared, with missing values handled and key variables selected for analysis.

### Analysis Steps
The analysis conducted in the Jupyter notebook includes:
1. **Data Cleaning and Preparation**: Renaming columns, handling missing values, and converting data types.
2. **Descriptive Statistics and Visualizations**: Histograms for Age and Year, and a summary of outliers and key statistics.
3. **Probability Mass Function (PMF) and Cumulative Distribution Function (CDF) Analysis**: Analysis of age distributions for wild vs. captive incidents.
4. **Analytical Distribution Fit**: Overlay of normal distribution on the Age variable to assess fit.
5. **Scatter Plot and Correlation Analysis**: Scatter plots for Age vs Year and Age vs Only one killed, along with correlation coefficients.
6. **Logistic Regression Analysis**: A logistic regression model to predict incident type (wild vs. captive) based on Age and Year.

### Key Findings
The analysis supports partial validation of the hypothesis:
- **Wild incidents** affect a broader age range, with more variation in age, suggesting random interactions in natural settings.
- **Captive incidents** are more concentrated in certain age groups, likely due to the controlled nature of these environments.

### Limitations and Future Research
- **Limitations**: The dataset is relatively small, and certain key variables, such as specific location and bear behavior, were not available.
- **Future Research**: Expanding the dataset and including variables like location type, visitor behavior, and bear characteristics would improve prediction accuracy and provide more comprehensive insights into bear incidents.

### How to Use This Repository
1. **View the PowerPoint Presentation**: The presentation provides a summary of the project, findings, and conclusions.
2. **Explore the Dataset**: The dataset can be examined to understand the variables used in the analysis.
3. **Run the Notebook**: The Jupyter notebook includes code for data analysis, visualizations, and statistical tests. You can rerun the cells to replicate the analysis.
