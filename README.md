# Palmer Penguins Analysis

## Overview
This is an exploratory data analysis (EDA) project using the **Palmer Penguins dataset**, which contains data on 344 penguins from three species: Adelie, Chinstrap, and Gentoo, observed across three islands in the Palmer Archipelago, Antarctica. The data were collected by Dr. Kristen Gorman.

The goal of this analysis is to examine the physical characteristics of each species, explore ecological differences across islands, and visualize key relationships within the dataset.

---

## Business Question
**How do the three penguin species differ in physical characteristics, and what ecological patterns exist across their island habitats?**

---

## Tools Used
- **R**: data cleaning, analysis, and visualization
- **tidyverse**: data manipulation and visualization
- **ggplot2**: data visualization
- **palmerpenguins**: dataset
- **RStudio**: development environment

---

## Key Findings
- **Gentoo penguins are the largest species**, with the highest average body mass (~5,076g) and longest flippers
- **Chinstrap penguins have the longest bills** on average (48.8mm), while Adelie have the shortest (38.8mm)
- **Gentoo penguins have the highest bill ratio (3.18)**, meaning longer, narrower bills relative to depth
- **There is a strong positive correlation (r = 0.87)** between flipper length and body mass across all species
- **Sex distribution is remarkably balanced**: Adelie and Chinstrap are exactly 50/50, Gentoo is 48.7% female and 51.3% male
- **Biscoe Island has the heaviest penguins** on average (avg body mass ~4,716g), dominated by Gentoo
- **Adelie is the only species found across all three islands**

---

## Visualizations
| Chart | Description |
|-------|-------------|
| `bill_ratio_by_species.png` | Violin + boxplot showing bill ratio distribution by species |
| `body_mass_vs_flipper_length.png` | Scatter plot showing correlation between flipper length and body mass |
| `male_vs_female_count_by_species.png` | Bar chart showing sex distribution across species |
| `penguin_species_count_by_island.png` | Stacked bar chart showing species distribution across islands |

---

## Files
- `palmer_penguins_analysis.Rmd`: full analysis with code and explanations
- `palmer_penguins_analysis.pdf`: formatted report
- `PNG charts`: data visualizations

---

## Data Source
[palmerpenguins R package](https://allisonhorst.github.io/palmerpenguins/): data collected by Dr. Kristen Gorman, Palmer Station Antarctica LTER.

---

*Analysis completed by Daniel Eniola*
