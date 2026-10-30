# Rolling Stone Album Analysis Project

A data-driven exploration of the Rolling Stone Top 500 Greatest Albums using the CRISP-DM framework, built with R and Quarto.

------------------------------------------------------------------------

## Project Overview

This project investigates the historical distribution, critical reception trends, and demographic factors (such as artist gender and group structure) within the *Rolling Stone* Top 500 Greatest Albums dataset. As an archival and curation specialist for a digital streaming platform, this analysis extracts data-driven insights to inform catalog acquisition, editorial curation, and recommendation strategies.

Following the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology, the analysis systematically proceeds from business understanding through reproducible, deployment-ready insights using R and Quarto.

------------------------------------------------------------------------

## Project Directory Structure

``` text
rolling-stone-analysis/
│
├── data/
│   └── rolling_stone.csv         # Raw dataset containing album details, rankings, and release info
│
├── report.qmd                    # Quarto source document (contains all R code, analysis, and narrative)
├── report.html                   # Rendered HTML report with dynamic inline code and interactive charts
├── rolling-stone-analysis.Rproj  # RStudio Project file
└── README.md                     # Project documentation (this file)
```

------------------------------------------------------------------------

## Requirements & Environment

To run or render this project locally, ensure you have the following installed:

- **R** (version 4.6.1)
- **RStudio**
- Required R Packages:
  - `tidyverse` (includes `ggplot2`, `dplyr`, `readr`, etc.)
  - `quarto`

------------------------------------------------------------------------

## How to Run the Analysis

1.  Clone or download this repository to your local machine.
2.  Open the project by double-clicking `rolling-stone-analysis.Rproj` in RStudio.
3.  Ensure the `data/rolling_stone.csv` file is in place.
4.  Open `report.qmd` and click **Render** in RStudio, or run the following command in your R console:

``` r
quarto::quarto_render("report.qmd")
```

5.  Open the generated `report.html` in any web browser to view the final interactive report.
