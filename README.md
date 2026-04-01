# Palmer Penguins Analysis

## Overview

This project presents an exploratory data analysis (EDA) of the Palmer Penguins dataset, focusing on identifying differences in physical characteristics across species and uncovering ecological patterns across island habitats.

The dataset contains observations of 344 penguins from three species: Adelie, Chinstrap, and Gentoo, collected across three islands in the Palmer Archipelago, Antarctica by Dr. Kristen Gorman.

---

## Objective

**How do the three penguin species differ in physical characteristics, and what ecological patterns exist across their island habitats?**

This question is explored through summary statistics, visualization, and correlation analysis.

---

## Tools Used

* **R**: data cleaning, analysis, and visualization
* **tidyverse**: data manipulation and visualization (includes ggplot2)
* **palmerpenguins**: dataset
* **RStudio**: development environment

---

## Project Highlights

* Data cleaning and handling of missing values using `na.rm = TRUE`
* Feature engineering through creation of `bill_ratio`
* Use of multiple visualization types including violin plots, scatter plots, and bar charts
* Statistical validation using Pearson correlation analysis

---

## Key Findings

* **Gentoo penguins are the largest species**, with the highest average body mass (~5,076 g) and longest flippers
* **Chinstrap penguins have the longest bills** on average (48.8 mm), while Adelie have the shortest (38.8 mm)
* **Gentoo penguins have the highest bill ratio (3.18)**, indicating longer and narrower bills relative to depth
* **There is a strong positive correlation (r = 0.87)** between flipper length and body mass across all species
* **Sex distribution is remarkably balanced**: Adelie and Chinstrap are exactly 50 percent each, while Gentoo is 48.7 percent female and 51.3 percent male
* **Biscoe Island has the heaviest penguins** on average (~4,716 g), largely influenced by the presence of Gentoo penguins
* **Adelie is the only species found across all three islands**, indicating broader habitat distribution

---

## Visualizations

| Chart                                 | Description                                                           |
| ------------------------------------- | --------------------------------------------------------------------- |
| `bill_ratio_by_species.png`           | Violin and boxplot showing bill ratio distribution by species         |
| `body_mass_vs_flipper_length.png`     | Scatter plot showing correlation between flipper length and body mass |
| `male_vs_female_count_by_species.png` | Bar chart showing sex distribution across species                     |
| `penguin_species_count_by_island.png` | Stacked bar chart showing species distribution across islands         |

---

## Files

* `palmer_penguins_analysis.Rmd`: full analysis with code and explanations
* `palmer_penguins_analysis.pdf`: formatted report
* `.png` files: exported data visualizations

---

## Data Source

[palmerpenguins R package](https://allisonhorst.github.io/palmerpenguins/): data collected by Dr. Kristen Gorman, Palmer Station Antarctica LTER.

---

*Analysis completed by Daniel Eniola*
