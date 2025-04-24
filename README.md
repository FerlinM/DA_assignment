# UNICEF Global Report: The Twin Pillars of Child Development

## Examining Education Access and Preventive Healthcare Worldwide

This repository contains a comprehensive data analysis of two critical UNICEF indicators:
1. **Primary School Out-of-School Rates**: Measuring the percentage of children who should be enrolled in primary education but are not attending school
2. **HPV Vaccination Coverage**: Tracking the percentage of 15-year-old females who have received the complete human papillomavirus vaccine series

## Project Overview

This project analyzes global disparities in education access and preventive healthcare, demonstrating the significant differences that exist between regions and countries, as well as the progress being made in addressing these challenges.

### Key Findings

- Significant regional disparities exist in both education access and HPV vaccination rates
- Sub-Saharan Africa and parts of South Asia face the greatest education access challenges
- Countries like Australia, Norway, and Iceland have achieved high HPV vaccination rates, while many low-income countries are still developing their programs
- There is a moderate correlation between education access and healthcare provision

## Repository Contents

- `unicef_report.qmd`: Quarto document containing all analysis code and narrative
- `unicef_report.html`: Rendered HTML report of the analysis (what you'll see on the website)
- `index.html`: Entry point for the GitHub Pages site
- `dataset/`: Folder containing all data files used in the analysis
  - `unicef_indicator_1.csv`: Primary education out-of-school rate data
  - `unicef_indicator_2.csv`: HPV vaccination rate data
  - `unicef_metadata.csv`: Additional metadata for the indicators

## Viewing the Report

You can view the rendered report at: [https://ferlinm.github.io/DA_assignment/unicef_report.html](https://ferlinm.github.io/DA_assignment/unicef_report.html)

## Methodology

The analysis uses Python for data processing and visualization, with libraries including:
- pandas and numpy for data manipulation
- matplotlib, plotnine, and seaborn for visualization
- geopandas for mapping
- scikit-learn for correlation analysis

## Author

Ferlin Martin - April 24, 2025

## Acknowledgments

- UNICEF for providing the open data used in this analysis
- The Quarto project for document creation tools
