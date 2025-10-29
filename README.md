
# Homework {num}: Spatial Data Analysis (Subject)

This repository contains the complete analysis for Homework {num} of the Spatial Data Analysis course (MATH-6384). {Brief description of homework subject}.

- Author: E. Duke Chase
- Course: MATH-6384, Spatial Data Analysis
- Due Date: 2025-mm-dd

## Repository Contents
This project is structured as a reproducible R environment using `renv` and Quarto.
- `2025-mm-dd_sda_homework-{num}.qmd`: The main Quarto document containing all code and analysis.
- `R/setup.R`: The R script that loads packages and sets global options.
- `_quarto.yml`: The project configuration file, which sets the HTML theme and other rendering options.
- `data/`: Contains raw data files used in the analysis. The contents of this folder are ignored by git.
- `output/`: Contains saved results like cached computations or exported plots. The contents of this folder are ignored by git.
- `renv.lock` / `.Rprofile`: Files that ensure the R environment is fully reproducible.

## How to Reproduce the Analysis
To run this analysis and render the final HTML report, please follow these steps:

1. Clone the Repository

```r
git clone <repository-url>
```

2. Open the Project: Open the `2025-mm-dd_sda_homework-{num}.Rproj` file in RStudio.

3. Restore the Environment: Run the following command in the R console. This will install the exact versions of all R packages used in the analysis.

```r
renv::restore()
```

4. Render the Document: 
Open the `2025-mm-dd_sda_homework-{num}.qmd` file and click the "Render" button, or run the following command in the R console:

```r
quarto::quarto_render("2025-mm-dd_sda_homework-{num}.qmd")
```
