# Observational Study R Tutorials

This repository provides a comprehensive guide to conducting causal inference in observational studies using R. Each tutorial covers a key topic in observational study analysis, focusing on techniques like propensity score matching, nearest neighbor matching, and balance checking. These methods are crucial for minimizing confounding and drawing more accurate causal conclusions in non-experimental data.

## Tutorials

1. **Nearest Neighbor Matching**: Perform 1-to-1 greedy matching to balance treated and control groups.
2. **Balance Checks**: Verify covariate balance before and after matching to ensure effective matching.

## Getting Started

1. **Install R and MatchIt**: Ensure you have R installed and the `MatchIt` package (`install.packages("MatchIt")`).
2. **Run in Google Colab**: Run these scripts in Google Colab by setting up the R environment with the `rpy2` library.
3. **Use Sample Data**: Each script includes example data generation or can work with data in the `data/` folder.

## Skills Demonstrated

- **Causal Inference**: Applying causal inference techniques in R to adjust for confounding.
- **Propensity Score Matching**: Calculating and applying propensity scores in matching algorithms.
- **Data Balancing**: Ensuring covariates are balanced between treatment groups.
- **Nearest Neighbor Matching**: Using `MatchIt` for practical nearest neighbor matching on real-world data.
