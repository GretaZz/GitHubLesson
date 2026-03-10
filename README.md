# Penguin Analysis

A reproducible analysis of morphological measurements from the Palmer Penguins dataset, examining variation in body dimensions across penguin species in the Palmer Archipelago, Antarctica.

<img src="https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png" width=50%>


## About the Data

This project uses data collected by [Dr Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php) at the [Palmer Station Long Term Ecological Research](https://pallter.marine.rutgers.edu/) site in Antarctica.

**Species studied:** Gentoo, Chinstrap, and Adelie penguins. 

**Research location:** Torgersen, Biscoe, Dream islands.

**Sample size:** 344

**Years of data collection:** 2007, 2008, 2009.

## Variables Measured

The dataset includes the following morphological measurements:

| Variable | Range |
|----------|-------------|
| `bill_length_mm` | [TODO: Include range] |
| `bill_depth_mm` | [TODO: Include range] |
| `flipper_length_mm` | [TODO: Include range] |
| `body_mass_g` | [TODO: Include range] |

## What the Analysis Does

The R script `run_analysis_SOLUTIONS.R` performs the following steps:

1. **Data cleaning** -- The cleaning section drops NA in selected columns: species, bill_length_mm, flipper_length_mm
2. **Exploratory boxplots** -- Plotted bill_length_mm against species.
3. **Cluster analysis** -- [TODO: Which two measurements are used to show how species cluster? Hint: look at section 7]
4. **Regression analysis** -- [TODO: What relationship does the regression plot examine? Hint: look at section 7]

## Plots Produced

The analysis generates a multi-panel figure combining four plots:

- **Top left:** This is a boxplot of bill length by species
- **Top right:** This is a boxplot of flipper length by spcies
- **Bottom left:** This is a cluster plot of bill length and flipper length by species
- **Bottom right:** This is a regression plot of bill length and flipper length by species - linear regression

<img width="1024" height="640" alt="image" src="https://github.com/user-attachments/assets/11930fe4-f81e-4362-bf7e-1e1d234873c7" />




## Authors

Greta Zordan


