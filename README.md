# Exploring a Large Synthetic Hospital Dataset

## Project Overview

This project presents an exploratory analysis of a large synthetic hospital database containing information on patients, healthcare encounters, diagnoses, medications, departments, and providers. The analysis was conducted as an introduction to working with a large, unfamiliar relational healthcare dataset.

The project is framed around a hypothetical hospital-system merger in which the hospital data must be characterized and evaluated before integration into a larger analytics database. The primary objectives were to understand the structure and quality of the data, identify important patterns, assess missing and unreasonable values, and document potential issues that could affect future analyses.

## Objectives

The analysis addresses the following areas:

* Importing and cleaning multiple relational data tables
* Converting nonstandard missing-value codes into appropriate R missing values
* Summarizing patients, encounters, medications, diagnoses, departments, and providers
* Joining related tables to identify common diagnoses, medications, departments, and providers
* Calculating body mass index from encounter-level height and weight measurements
* Examining length of stay across patient and departmental groups
* Visualizing patient age, encounter frequency, and BMI patterns
* Assessing missingness, duplicate records, and unreasonable values
* Identifying each patient's most recent valid BMI measurement
* Comparing recorded encounter ages with ages calculated from birth and admission dates

## Data

The dataset represents an imaginary hospital database and is completely synthetic. It does not contain information from real patients.

The original CSV files are not included in this repository because of their size and redistribution limitations. Consequently, the Quarto source file cannot be rerun without access to the original  dataset. The rendered HTML report contains the complete results, tables, visualizations, and R code used in the analysis.

## Tools and Packages

The analysis was completed in R and Quarto using packages including:

* `tidyverse`
* `lubridate`
* `knitr`

## Skills Demonstrated

* Exploratory data analysis
* Data cleaning and validation
* Relational data joins
* Missing-data assessment
* Healthcare data analysis
* Data visualization with `ggplot2`
* Reproducible reporting with Quarto
* Communication of technical findings to nontechnical stakeholders

## Repository Contents

* `hospital_data_exploration.qmd`: Quarto source file containing the narrative and R code
* `index.html`: Self-contained rendered report
* `README.md`: Project description and documentation

## Viewing the Analysis

Open `index.html` to view the complete rendered report. When GitHub Pages is enabled, the report can also be viewed directly as a webpage.

## Author

Sabine Umuhire
