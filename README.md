# Canadian Language Attitudes: Plots and Data

Code and data for reproducing the figures in:

> Dollinger, S., & Hinrichs, L. (2026). Canadian language attitudes from "coast to coast to coast": On the pluricentricity of English. In J. Walker, D. Loakes & K. Gnevsheva (eds.), *Perceptions and attitudes in multilingual contexts*. Special issue, *Australian Journal of Linguistics*, 46(2).

## Contents

- `index.qmd` — Quarto source file with R code for all figures
- `index.html` — Rendered output (viewable at https://dollinger-hinrichs-2025.netlify.app)
- `data/`
  - `df_cleaned.csv` — Main survey dataset (N ≈ 3,000)
  - `data_fig_3_1.csv` — Dictionary usage data
  - `data_fig_3_2.csv` — Press mentions data
  - `figure7a.csv` — Canadian way of speaking by biography
  - `figure7b.csv` — Canadian way of speaking by gender

## Requirements

R packages: `tidyverse`, `rio`, `janitor`, `patchwork`, `showtext`, `scales`

Install via:
```r
install.packages("pacman")
pacman::p_load(rio, tidyverse, janitor, patchwork, showtext, sysfonts, scales)
```

## License

Data and code: CC BY 4.0# dollinger-hinrichs-2026
