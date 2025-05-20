# TeamPeru: CSC3107-Information Visualisation 

This repository contains Team Peru's weekly lab assignments for a data visualization and analysis course. The labs focuses on cleaning, manipulating, and visualizing data using R and the tidyverse ecosystem.

## Repository Structure

### Lab Contents

#### Week 2: Data Cleaning and Manipulation
The Week 2 lab (`week2_lab.qmd`) includes:

- **Country-Level Statistics from the World Bank**
    - Importing and cleaning economic indicators
    - Filtering to actual countries
    - Adding continent information
    - Formatting and validating the dataset

- **Population Statistics for Singapore**
    - Importing and parsing population data by age groups
    - Cleaning and restructuring data
    - Processing age ranges and cohort sizes

#### Week 3: Exploring ggplot2
The Week 3 lab (`Peru_P1_Week3Lab.qmd`) focuses on data visualization:

- **Visualizing Distribution of Penguin Bill Lengths**
    - Scatter plots, jitter plots, and bee-swarm plots
    - Violin plots with boxplots
    - Frequency polygons with rug plots
    - Statistical analysis with pairwise t-tests

- **Mitigating Overplotting**
    - Various techniques to address overplotting in scatterplots
    - Jittering and transparency
    - Point area proportional to count
    - Smoothing trends (LOESS and linear models)

## Required Packages

The project uses the following R packages:
- `tidyverse` (dplyr, ggplot2, tidyr, etc.)
- `readxl`
- `countrycode`
- `waldo`
- `palmerpenguins`
- `ggbeeswarm`

## Usage

1. Clone this repository
2. Open the `lab2_TeamPeru.Rproj` file in RStudio
3. Navigate to the individual `.qmd` files to view and run the analyses
4. Use `quarto render` to generate HTML reports from the `.qmd` files

## Team Peru Members

This repository contains collaborative work from Team Peru members for the data visualization course.
