# Dentists Worldwide Analysis

This repository contains an R-based analysis of the number of dentists worldwide, using data from the World Health Organization (WHO).

## Data

The dataset used in this analysis is `dentistas_mundo_who.csv`. It contains the following columns:

| Column                                  | Description                                           |
| --------------------------------------- | ----------------------------------------------------- |
| `Country`                               | The name of the country.                              |
| `Year`                                  | The year of the record.                               |
| `Number of dentistry personnel`         | The total number of dentistry personnel.              |
| `Number of dentists`                    | The number of dentists.                               |
| `Number of dental technicians/assistants` | The number of dental technicians and assistants.      |

## Analysis

The analysis is performed in the `dentists_worldwide.Rmd` R Markdown file. It loads the dataset, and then calculates the average number of dentists per country for the years after 2000.

## How to Run

To reproduce the analysis and generate the HTML report, you will need to have R and RStudio installed.

1.  Open the `dentists_worldwide.Rproj` file in RStudio.
2.  Open the `dentists_worldwide.Rmd` file.
3.  Click the "Knit" button in RStudio to run the R Markdown file. This will generate the `dentists_worldwide.nb.html` file.
