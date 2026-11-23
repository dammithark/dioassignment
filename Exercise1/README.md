# Exercise 1 – Exploratory Data Analysis & Automated Reporting with Pandas

**Notebook:** `Exercise1._YourFullName.ipynb`

## Objective
Generate data programmatically, compute statistical aggregates, visualise them, and export the results to a spreadsheet.

## Steps performed
1. Created a DataFrame of 100 rows with columns `f1`–`f4`, filled with random values in the range 0–100 (NumPy random generator, seed 42 for reproducibility).
2. Plotted a scatter plot of `f2` against `f3` with axis labels and a title.
3. Computed the row-wise mean of `f1`–`f4` (`mean(axis=1)`) and stored it in a new column `f5`.
4. Exported the complete DataFrame (`f1`–`f5`) to `Exercise1_output.xlsx` and read it back to confirm the export.

## Output
![Scatter plot of f2 vs f3](Exercise1_scatter.png)

- Excel file: [Exercise1_output.xlsx](Exercise1_output.xlsx)

## Observations
- The scatter plot shows no visible pattern between `f2` and `f3`. The Pearson correlation is [value], close to zero. This is expected, because the columns were generated independently.
- Because `f5` is an average of four independent values, it varies less than any single column. Its range is [min]–[max], compared with 0–100 for `f1`–`f4`.
