# Early Onset Gastric Cancer Analysis

This repository contains data and preliminary analyses related to early-onset gastric cancer (EOGC). EOGC refers to gastric cancer diagnosed in individuals typically under the age of 40. While the overall incidence of gastric cancer has declined, cases among younger populations have shown a slight increase, accounting for approximately 5% of all gastric cancer diagnoses.

## Repository Contents

- **Data Files**:
  - `gastric_cancer_data.csv` – Raw data on gastric cancer cases.
  - `harris_county_population_2010-2023/` – Population data for Harris County, Texas, from 2010 to 2023.

- **Analysis Scripts**:
  - `prelim.Rmd` – R Markdown file with exploratory data analysis.
  - `prelim.pdf` – PDF version of the preliminary analysis.

- **Visualizations**:
  - `bubble_plot_with_legend.png` – Bubble plot with legend.
  - `bubble_plot_with_vertical_legends.png` – Bubble plot with vertical legends.
  - `simple_bubble_plot.pdf` – Simplified bubble plot.
  - `Rplots.pdf` – Compilation of generated plots.

## Objectives

The primary goals of this project are:

1. **Data Acquisition and Preprocessing**:
   - Compile and clean datasets on EOGC, focusing on demographics and clinical data.
   - Incorporate Harris County population data for incidence context.

2. **Exploratory Data Analysis (EDA)**:
   - Perform descriptive statistics.
   - Generate visualizations to identify patterns and potential correlations.

3. **Hypothesis Generation**:
   - Propose hypotheses on risk factors, trends, or geographic distributions.

## Dependencies

This project requires the following R packages:

- `tidyverse`
- `ggplot2`
- `dplyr`
- `readr`
- `knitr`
- `rmarkdown`

Install missing packages using:
```r
install.packages(c("tidyverse", "ggplot2", "dplyr", "readr", "knitr", "rmarkdown"))
```
