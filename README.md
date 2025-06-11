# Health Insurance Cost Analysis

# Project Overview

This project explores how personal characteristics and regional factors affect healthcare insurance charges. Using a dataset of insurance policyholders, I investigate patterns in cost distribution that can then be used to build predictive models to estimate healthcare expenses in the future.

The aim is to identify which features most strongly influence insurance charges based on user attributes and demographics.

# Hypothesis

Individuals who smoke, have a higher BMI, or are older will incur significantly higher insurance charges. Additionally, geographic region may contribute to variations in cost due to external factors such as cost of living, differing healthcare practices, or wider economic conditions.

# The Dataset

The dataset has been provided by Kaggle and includes the following columns:
- Age: Age of primary beneficiary 
- Sex: Gender (encoded)
- BMI: Body Mass Index
- Children: Number of dependents covered by insurance
- Smoker: Smoking Status
- Region: Residential area in the US (northeast, southeast, southwest, northwest).
- Charges: Individual medical costs billed by health insurance

# Ethics

The dataset used did not contain any personal or identifiable information in the set.

# Objectives

Understand how personal and regional factors correlate with insurance charges
Visualize relationships using scatter plots and correlation analysis
Evaluate model performance and feature importance

# Methods & Tools

- Python, 
- pandas Library, 
- NumPy 
- Matplotlib 
- Seaborn for visualisations
- Jupyter Notebook for analysis and documentation

# Key Insights from Data Analysis 
Below are the key findings from the analysis of factors influencing healthcare insurance charges. 

- Smoking has the strongest impact on healthcare insurance costs. When other variables are held constant, smokers pay nearly three times more than non-smokers on average.
- The box plot shows a clear separation in charges based on smoking status. Smokers have consistently higher charges, with no significant outliers. In contrast, non-smokers display many high-cost outliers, suggesting that other factors — such as age and BMI — also drive up charges.
- Higher BMI and older age are both associated with increased insurance costs. Individuals who are smokers, older, and have a BMI above 30 are typically among those with the highest charges.
- Regional differences are evident: the Northwest and Southwest regions show lower average charges, while the Southeast has the highest costs among all four regions analyzed.
- The number of children does not significantly influence charges.
- There is a positive correlation between age and charges, especially among smokers.
- Gender does not show a strong impact on charges when other variables are controlled.

# Further Investigation

This analysis used exploratory visualizations to uncover how smoking status, BMI, age, and region relate to healthcare insurance costs. To build a more complete picture, future datasets should include data on pre-existing medical conditions, as these likely have a major impact on charges. Capturing such information could help identify specific risk profiles and enable the creation of custom insurance products for high-risk groups.
Looking ahead, applying statistical models — such as linear regression or decision trees — would allow for deeper insights and more accurate predictions about which factors most influence insurance costs.

# References

Resources used include:

Code Institute LMS https://learn.codeinstitute.net/ci_program/daai_5

ChatGPT https://chatgpt.com/

Data to Viz https://www.data-to-viz.com/

# Acknowledgements

Thanks to John Readon and Vasi Pavaloi for support on a number of IT issues.

