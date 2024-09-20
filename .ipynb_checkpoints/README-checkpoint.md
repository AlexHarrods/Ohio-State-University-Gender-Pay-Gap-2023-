# Ohio State University Earnings 2023: Gender Pay Gap Analysis

This repository contains an analysis of the gender pay gap at Ohio State University using the "Ohio State University 2023 Combined Earnings" dataset. The project explores gender disparities in gross pay, bonuses, overtime, and other forms of compensation across different employee position groups.

## Table of Contents
# Table of Contents

1. [Gender Pay Gap Analysis in Ohio State University](#1-gender-pay-gap-analysis-in-ohio-state-university)
2. [Import Necessary Libraries](#2-import-necessary-libraries)
3. [Load and Examine the Dataset](#3-load-and-examine-the-dataset)
4. [Gender Distribution Overview](#4-gender-distribution-overview)
5. [Gross Pay and Gender](#5-gross-pay-and-gender)
   - 5.1 [Mean Gross Pay by Gender](#51-mean-gross-pay-by-gender)
   - 5.2 [Distribution of Gross Pay Categories](#52-distribution-of-gross-pay-categories)
   - 5.3 [Distribution of Gross Pay & Gender Categories](#53-distribution-of-gross-pay--gender-categories)
   - 5.4 [Mean and Median Gross Pay by Gender and Position Group](#54-mean-and-median-gross-pay-by-gender-and-position-group)
6. [Gender Pay Gap Analysis between Gross Pay, Bonuses, Overtime, and Gender](#6-gender-pay-gap-analysis-between-gross-pay-bonuses-overtime-and-gender)
   - 6.1 [Create Contingency Tables](#61-create-contingency-tables)
     - 6.1.1 [Regular Pay](#611-regular-pay)
     - 6.1.2 [Bonus](#612-bonus)
     - 6.1.3 [Other Compensation](#613-other-compensation)
     - 6.1.4 [Overtime](#614-overtime)
   - 6.2 [Visualize](#62-visualize)
   - 6.3 [Observations](#63-observations)
   - 6.4 [Conclusions](#631-conclusions)
7. [Tests](#7-tests)
   - 7.1 [Chi-Square Test](#71-chi-square-test)
   - 7.2 [Mann-Whitney Test](#72-mann-whitney-test)
8. [Gender Pay Gap Analysis by Position Group](#8-gender-pay-gap-analysis-by-position-group)
   - 8.1 [Create a Dataset](#81-create-a-dataset)
   - 8.2 [First Look](#82-first-look)
   - 8.3 [Gross Pay](#83-gross-pay)
     - 8.3.1 [Distribution of Gross Pay Categories](#831-distribution-of-gross-pay-categories)
     - 8.3.2 [Viz 1](#832-viz-1)
     - 8.3.3 [Viz 2](#833-viz-2)
     - 8.3.4 [Observations](#834-observations)
   - 8.4 [Overtime](#84-overtime)
     - 8.4.1 [Distribution of Overtime Categories](#841-distribution-of-overtime-categories)
     - 8.4.2 [Viz 1](#842-viz-1)
     - 8.4.3 [Viz 2](#843-viz-2)
     - 8.4.4 [Remove Values Below Zero](#844-remove-values-below-zero)
     - 8.4.5 [Observations](#845-observations)
9. [General Conclusion](#9-general-conclusion)
10. [Recommendations](#10-recommendations)

## Project Overview
The primary goal of this project is to analyze the gender pay gap at Ohio State University. By looking at regular pay, bonuses, overtime, and other compensations, we aim to determine whether significant gender-based pay differences exist, and to what extent these are influenced by employee position groups.

## Dataset Description
The dataset used in this project is the modified "Ohio State University 2023 Combined Earnings" dataset, which includes data such as:
- full_name
- gender
- position_group
- job hierarchy
- cost_center
- regular_pay
- bonus
- other
- overtime
- gross_pay

## Project Structure and Analysis Details
1. **Gender Pay Gap Analysis in Ohio State University**: Introduction to the research question and overview.
2. **Import Necessary Libraries**: Code to load the required libraries for the analysis.
3. **Load and Examine the Dataset**: Initial exploration of the dataset, including checking for missing values and outliers.
4. **Gender Distribution Overview**: Provides an overview of the gender distribution in the dataset.
5. **Gross Pay and Gender**: An analysis of how gross pay is distributed across genders.
6. **Gender Gap Analysis**: Evaluation of how each compensation type is distributed across genders using contingency tables and visualizations.
7. **Statistical Tests**: 
- **Chi-Square Test**: This test checks whether there is a significant association between gender and pay categories.
- **Mann-Whitney Test**: This non-parametric test is used to compare pay distributions between genders.
8. **Gender Gap by Position Group**: A look at the gross pay and overtime distribution across different position groups, and how these differ by gender.
9. **Conclusion**: This analysis provides insights into gender-based pay disparities at Ohio State University. Statistical tests reveal where significant differences exist, and the findings highlight areas for potential action.
