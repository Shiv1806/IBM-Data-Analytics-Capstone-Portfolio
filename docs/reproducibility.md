# Reproducibility Notes

## Python notebooks

The supplied notebooks retain the source URLs used in the IBM Skills Network course exercises.

Some notebooks download datasets at runtime rather than reading a local copy. An internet connection may therefore be required when executing them from a clean environment.

## Python environment

Install the packages listed in `requirements.txt`.

The notebooks use Python with Pandas, NumPy, Matplotlib, Seaborn, Requests, BeautifulSoup, and related data-access libraries.

## Web scraping

`05_web_scraping.ipynb` extracts programming-language salary information from the provided Programming Languages page and saves the result to `data/popular-languages.csv`.

## Cognos dashboard

The Cognos dashboard screenshots are included as portfolio evidence. The original IBM Cognos Analytics report/package and its underlying Cognos data model were not included in the supplied files, so the dashboard cannot be recreated directly from this repository alone.

This repository therefore separates reproducible notebook work from the dashboard presentation layer.
