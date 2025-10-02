# Clustering-of-Economic-Indicators
This project is ongoing and being regularly updated.

In this project, I explore applications of spectral clustering algorithms to analyze countries' macroeconomic indicators.

Notes on the code in .ipynb (by cells):
- IMPORTANT: do not execute Cell 1.4 unless 1.3 fails. In this case, use .csv. ISSUE with Cell 4.3: flawed outputs due to dictionary indexing mismatches, fix is underway.
- Cell 1.1: the code was written for working in a Google Colab (Jupyter notebook) environment. Modify for other environments, i.e. "pip install wbdata".
- Cell 1.3: downloads data from the World Bank Development Indicators database. Not always reliable, alternatively run 1.4 with local .csv file.
- Cell 1.4: choose the .csv file for the year you want, i.e. g1_backup_2023.csv for the year 2023 (additional years will be uploaded).
- Cell 3.1: the function computes the inverse matrix of Scott's 2D bandwidth matrix, not the bandwidth matrix itself
- Cell 4.2: for the year 2023, you may find the output under cluster_plot_yyyy_k.png for year = yyyy and number of clusters k (e.g. cluster_plot_2023_9.png).
