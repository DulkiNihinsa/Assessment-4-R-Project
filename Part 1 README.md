# README for RNA-seq and Tree Growth Data Analysis Project

This project analyzes RNA-seq gene expression count data and tree growth measurements from two different sites. It calculates summary statistics, identifies genes with highest and lowest expression, visualizes gene expression distribution, and evaluates tree growth differences between sites using statistical tests.

## Included files

- gene_expression.tsv: Tab-separated file containing RNA-seq gene count data with gene IDs as row identifiers.
- growth_data.csv: CSV file containing tree circumference measurements at start and end times for control and treatment sites.
- Part 1.Rmd: R Markdown that performs data import, calculation of means, standard deviations, statistical tests, and produces plots.
- README.md: Documentation file explaining project purpose, included files, how to run the analysis, and contributors.

## How to run the code

1. Place all input files (gene_expression.tsv and growth_data.csv) in the working directory.
2. Open RStudio.
3. Run the R Markdown `Part 1.Rmd` line-by-line or as a whole to perform the analyses and generate outputs.
4. Outputs include printed summary tables and visual plots (histogram and boxplots).

## Contributors

Dulki Nihinsa Danthanarayana - performed data analysis, script creation, project oversight and documentation