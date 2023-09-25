# Sampling with Python

This repository contains Python notebooks for two projects focused on sampling techniques and statistical analysis using Python.

## Project 1: Constructing a Confidence Interval

### Overview
In this project, we'll continue with our previous scenario, where you're a data professional working for the Department of Education of a large nation. Previously, you collected data on district literacy rates and used Python to simulate taking a random sample of 50 districts and make a point estimate of the population mean literacy rate. Now, you are tasked with constructing a 95% confidence interval for your estimate of the mean district literacy rate.

### Confidence Interval and Confidence Level
You may notice that as the confidence level gets higher, the confidence interval gets wider. For example:
- With a confidence level of 95%, the interval covers 5.6 percentage points (71.4% - 77.0%).
- With a confidence level of 99%, the interval covers 7.4 percentage points (70.5% - 77.9%). This wider interval is more likely to include the actual population parameter.

Your results will help the Department of Education decide how to distribute government resources to improve literacy.

## Project 2: Analyzing Air Quality Data

### Introduction
The Air Quality Index (AQI) is the Environmental Protection Agency's index for reporting air quality. A value close to 0 signals little to no public health concern, while higher values are associated with increased risk to public health. Your role as a data analyst in the Strategy division of Ripple Renewable Energy (RRE) is to identify which U.S. states are most likely to be affected by a new federal policy that would create a subsidy for renewable energy in states observing an average AQI of 10 or above.

### Tasks for Analysis
For your analysis, you will:
- Provide a summary of the mean AQI for the states in which RRE operates.
- Construct a boxplot visualization for AQI of these states using seaborn.
- Evaluate which state(s) may be most affected by this policy, based on the data and your boxplot visualization.
- Construct a confidence interval for the RRE state with the highest mean AQI.

### Key Takeaways
- California and Michigan were most likely to have experienced a mean AQI above 10.
- With California experiencing the highest sample mean AQI in the data, it appears to be the state most likely to be affected by the policy change.
- Constructing a confidence interval allowed you to estimate the sample mean AQI with a certain degree of confidence.

### Findings to Share
- Present this notebook to convey the analytical process and describe the methodology behind constructing the confidence interval.
- Share that a 95% confidence interval from the sample data yielded [10.36 , 13.88], indicating a 95% confidence that the population mean AQI for California was between 10.36 and 13.88, which is notably greater than 10.
- Explain how varying the confidence level changes the interval (e.g., at a 99% confidence level, the interval would become [9.80 , 14.43]).

### Conveying to Stakeholders
- Explain statistical significance at a high level.
- Describe California's observed mean AQI and suggest focusing on that state.
- Share the result of the 95% confidence interval and its significance relative to the policy threshold of 10.
- Convey any potential shortcomings of this analysis, such as the short time period being referenced.

---

### Notebooks

1. [Project 1 - Constructing a Confidence Interval](project1.ipynb)
2. [Project 2 - Analyzing Air Quality Data](project2.ipynb)

Each project has its own notebook for detailed implementation and analysis.

Feel free to explore the notebooks in this repository to learn more about these projects and the techniques used for sampling and statistical analysis in Python.

