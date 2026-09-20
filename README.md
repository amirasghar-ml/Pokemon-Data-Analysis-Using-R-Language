# Pokemon Data Analysis — R Language

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-FF6F00?style=flat-square&logoColor=white)
![tidyverse](https://img.shields.io/badge/tidyverse-1A162D?style=flat-square&logoColor=white)

Comprehensive **Exploratory Data Analysis (EDA)** of the Pokemon dataset using R — uncovering stat distributions, type relationships, legendary patterns, and generation trends through rich visualizations.

---

## Analysis Highlights

- **Stat Distributions** — HP, Attack, Defense, Speed across all generations
- **Type Analysis** — which types dominate, type vs. base stat correlations
- **Legendary vs. Non-Legendary** — statistical comparison of legendary Pokemon
- **Generation Trends** — how base stats evolved across Gen 1–6
- **Correlation Matrix** — relationships between all numeric attributes
- **Top Performers** — highest attack, defense, speed, and overall Pokemon

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| R | Core analysis language |
| ggplot2 | Visualizations and plots |
| tidyverse | Data wrangling (dplyr, tidyr) |
| corrplot | Correlation heatmaps |
| ggcorrplot | Advanced correlation plots |

---

## Key Visualizations

- Bar charts of average base stats by type
- Scatter plots of Attack vs. Defense colored by type
- Boxplots of Speed distribution by generation
- Heatmap of correlation between all numeric features
- Density plots of HP for Legendary vs. Non-Legendary

---

## Getting Started

```r
# Install required packages
install.packages(c("tidyverse", "ggplot2", "corrplot", "ggcorrplot"))

# Run the analysis
source("analysis.R")
```

---

## Dataset

The Pokemon dataset contains **800 Pokemon** across 6 generations with features:
`Name`, `Type1`, `Type2`, `HP`, `Attack`, `Defense`, `Sp. Atk`, `Sp. Def`, `Speed`, `Generation`, `Legendary`

---

## Author

**Amir Asghar** — Senior AI/ML Engineer
[GitHub](https://github.com/amirasghar-ml) · [LinkedIn](https://www.linkedin.com/in/amir-asghar-ali-a80825112/)
