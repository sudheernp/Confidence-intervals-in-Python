# Confidence Intervals in Python

Welcome to the Confidence Intervals in Python project repository. This repository contains Python notebooks for two projects focusing on constructing confidence intervals and conducting statistical analysis using Python.

## Project 1: Constructing Confidence Intervals for Literacy Rates

### Overview
In this project, we'll continue with our previous scenario where you're a data professional working for the Department of Education of a large nation. Previously, you collected data on district literacy rates, took a random sample of 50 districts, and made a point estimate of the population mean literacy rate. Now, you are tasked with constructing a 95% confidence interval for your estimate of the mean district literacy rate.

### Relationship between Confidence Level and Interval Width
As the confidence level increases, the width of the confidence interval also increases. For example:
- With a 95% confidence level, the interval covers 5.6 percentage points (71.4% - 77.0%).
- With a 99% confidence level, the interval covers 7.4 percentage points (70.5% - 77.9%). A wider confidence interval is more likely to include the actual population parameter.

Your results will assist the Department of Education in making decisions on how to allocate government resources to improve literacy.

## Project 2: Analyzing Air Quality Data and Constructing Confidence Intervals

### Introduction
The Air Quality Index (AQI) is a crucial indicator of air quality, with higher values indicating increased health risks. The United States is contemplating a new federal policy to subsidize renewable energy in states with an average AQI of 10 or above.

As a data analyst in the Strategy division of Ripple Renewable Energy (RRE), your task is to analyze AQI data for the states in which RRE operates: California, Florida, Michigan, Ohio, Pennsylvania, and Texas. You will provide a summary of the mean AQI for these states, create boxplot visualizations, identify the state(s) most likely to be affected by the policy, and construct a confidence interval for the state with the highest mean AQI.

### Key Takeaways
- California and Michigan are most likely to have experienced a mean AQI above 10 based on the analysis.
- California, with the highest sample mean AQI in the data, appears to be the state most likely to be affected by the policy change.
- Constructing a confidence interval allowed us to estimate the sample mean AQI with a certain degree of confidence.

### Sharing Your Findings
- Use the provided notebooks to convey the analytical process and describe the methodology for constructing confidence intervals.
- Explain that a 95% confidence interval from the sample data yielded [10.36 , 13.88], indicating a 95% confidence that the population mean AQI for California was between 10.36 and 13.88, which is notably greater than the policy threshold of 10.
- Highlight how varying the confidence level changes the interval (e.g., a 99% confidence interval would be [9.80 , 14.43]).

### Conveying to External Stakeholders
- Provide an overview of statistical significance.
- Emphasize California's observed mean AQI and recommend focusing on that state.
- Share the result of the 95% confidence interval, describing its significance relative to the policy threshold of 10.
- Mention potential shortcomings of the analysis, such as the short time period being referenced.

---

### Notebooks

1. [Project 1 - Constructing Confidence Intervals for Literacy Rates](project1.ipynb)
2. [Project 2 - Analyzing Air Quality Data and Constructing Confidence Intervals](project2.ipynb)

Each project has its own notebook for detailed implementation and analysis.

Feel free to explore the notebooks in this repository to learn more about these projects and the techniques used for constructing confidence intervals and statistical analysis in Python.

