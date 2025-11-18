# NLSchools Language Achievement Analysis

## Description

This repository contains the R code and data for the **Analysis of Eighth-Grade Pupils in the Netherlands** project, utilizing the **`nlschools`** dataset from the `MASS` R package.

The primary objective of this study is to investigate the influence of student characteristics and classroom context on academic achievement, specifically focusing on **Language Exam Scores (`lang`)**. The analysis assesses the independent and interactive effects of Verbal IQ (`IQ`), Socioeconomic Status (`SES`), and Multigrade Class Status (`COMB`) on student performance.

## Installation Instructions

This project requires **R** and a few key R packages.
1.  **Install R and RStudio** (if you don't have them).
3.  **Install R Dependencies:**
    Open your R console and run the following command to install the required packages (e.g., `dplyr` for data manipulation, `ggplot2` for visualization, and `MASS` which originally housed the data).
    ```R
    install.packages(c("dplyr", "ggplot2", "MASS"))
    ```

## Usage
The main analysis is contained within the `nlschools_analysis.R` script.
1.  **Data File:** This project uses the exported data file **`nlschools_data.csv`**, which must be present in the root directory.
2.  **Run the Analysis Script:** Execute the main R script from your R console or RStudio:


### Key Analytical Questions Addressed
1.  Are there discrepancies in IQ or SES across different classes or when grouping by multi-grade vs. non-multi-grade classes?
2.  Which variables have the most important effects on the language exam score (`lang`)?
3.  Are there interaction effects (e.g., between IQ and Multigrade status) that influence the Language Exam score?
