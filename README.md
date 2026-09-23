# DATA301 – Assignment IV

Reproducible Quarto report for Assignment IV (Exercise 1: estimators of an exponential rate; Exercise 2: `ausbeer` time series).

## How to render

1. Install R (≥ 4.2) and Quarto (≥ 1.4).
2. Install the R packages:
   ```r
   install.packages(c("fpp2", "dplyr", "gridExtra", "knitr", "rmarkdown"))
   ```
3. Render from the repository folder:
   ```bash
   quarto render code/assignment4.qmd
   ```
   Or open `code/assignment4.qmd` in RStudio and click **Render**. The result is `code/assignment4.html`. The Monte Carlo experiment takes about 1–2 minutes.

Random seeds are fixed, so the numbers are reproducible.

## Files

- `code/assignment4.qmd` – the report (code + answers)
- `code/references.bib` – bibliography (must stay next to the .qmd)
