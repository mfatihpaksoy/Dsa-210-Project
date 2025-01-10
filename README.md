# Netflix Viewing Activity Analysis

## Project Overview
The project focuses on analyzing a Netflix dataset obtained directly from Netflix via a personal data request. The dataset includes various types of information such as user profile details, device usage, IP addresses, messages, and surveys. However, the primary focus will be on **viewing activity** to understand changes in personal streaming habits.

## Objective
- **Initial Engagement:** Initially, long viewing sessions were possible, with sustained usage in the app.
- **Recent Behavior:** There is a noticeable decline in session duration and an inability to watch content continuously in a single sitting.

## Project Files
- [main.ipynb](main.ipynb) - Main analysis notebook containing all visualizations and statistical tests
- [myData.csv](myData.csv) - Raw Netflix viewing activity data (not included in repository for privacy)
- [MySlides.pptx](MySlides.pptx) - Project report and presentation slides

## Methodology
### Dataset Preparation
- Extract relevant information related to viewing activity (e.g., timestamps, titles watched, session duration).
- Clean and preprocess the data for analysis.

### Categorization
- Organize the data into time periods (e.g., by year or month) to observe trends over time.

### Analysis and Visualization
- Use data visualization techniques such as:
  - Line charts to display trends in session duration.
  - Time series plots with moving averages
  - Distribution analysis of viewing durations
- Identify any significant shifts in usage behavior.

### Statistical Testing
- One-way ANOVA to test differences between years
- Log transformation for better distribution analysis
- Descriptive statistics by year

## Tools and Techniques
- **Software:** Python (pandas, matplotlib, seaborn)
- **Statistical Methods:** ANOVA, descriptive statistics
- **Visualization Techniques:** Time series plots, distribution plots

## Expected Outcome
- A comprehensive view of personal viewing habits over time.
- Insights into changes in streaming behavior, helping to understand what factors might have contributed to these shifts.
- Visualizations and statistical evidence to support the observations.

## Data Source
Data obtained through [Netflix's personal data download service](https://www.netflix.com/account/getmyinfo)

## Project Report
For detailed analysis and findings, please refer to the [project presentation slides](MySlides.pptx).
