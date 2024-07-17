# Overview

{Important!  Do not say in this section that this is college assignment.  Talk about what you are trying to accomplish as a software engineer to further your learning.}

As a software engineer, I aim to enhance my data analysis skills by exploring the performance metrics of UFC fighters. This project investigates the relationship between different methods of winning in UFC fights and fighter success.

The dataset used for this analysis was obtained from [Kaggle](https://www.kaggle.com/) and includes comprehensive records of UFC fights from 1993 to 2023, detailing winning methods and fighter performance metrics.

The purpose of writing this software is to analyze the data, identify patterns in winning methods, and assess their effectiveness. This analysis will help understand the dynamics of fighter success and the impact of different winning strategies in UFC matches.

[Software Demo Video](https://www.loom.com/share/64273bcab8574d639a22d0d2ff9b2b51?sid=22264f2c-760d-4418-9d01-589c07fef342)

# Data Analysis Results

Question: Is there a statistically significant association between winning method and fighter success in UFC matches?

Answer: Yes, the chi-squared test results reveal a statistically significant association (χ² = 217.5, df = 8, p < 2.2e-16).

Question: Are there differences in winning methods between fighters in the red and blue corners?

Answer: Yes, victories by submission and decision are more prevalent in the red corner, while knockouts (KO/TKO) are more balanced between the red and blue corners.

# Development Environment

Tools: RStudio, Jupyter Notebook

Programming Language: R

Libraries: tidyverse, mosaic, rio, ggplot2, ggrepel, pander

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [R Documentation](https://www.rdocumentation.org/)
* [Kaggle](https://www.kaggle.com/)
* [Tidyverse](https://www.tidyverse.org/)


# Future Work

Improve the analysis by incorporating more variables such as fighter weight class and fight location.

Enhance data visualization to provide more intuitive insights.

Develop a predictive model to forecast fight outcomes based on historical data.