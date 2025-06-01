# HRP 203 Spring 2025 Repository for Vikram Fielding-Singh

This repository includes simulated data and assignments for HRP 203 in Spring 2025.

The raw data is a csv file for `cohort` (located in the in the `raw-data` folder) includes 5,000 observations with variables `smoke`, `female`, `age`, `cardiac`, and `cost`.

There are two analysis files with corresponding output:

## Assignment 2
The analysis, archived in the directory assignment2, examines whether smoking is significantly associated with cost. First, general descriptive statistics are generated. Then some figures are used to display the relationships between two variables. The table and figure show that cost is higher in smokers. A linear regression model is then fit, adjusting for age, female, cardiac, and smoke. In the adjusted linear regression model, smoke is associated with 542 [95% CI 526 to 558] of additional cost.

Dependencies for this code: pacman, tidyverse, rmarkdown, readxl, table1, ggplot2, geepack

## Assignment 4
This analysis is located in the home directory. The .qmd file produces a reproducible document that conducts a similar analysis as Assignment 2, but with better implementation of reproducible methods.

Dependencies for this code: pacman, tidyverse, rmarkdown, readxl, table1, ggplot2, geepack, here

## Generative AI Statement
No generative AI technology was used to complete any portion of this assignment.
