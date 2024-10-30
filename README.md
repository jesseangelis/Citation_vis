# Citation Visualization Notebook

This notebook visualizes citation data for scholarly articles by retrieving and processing citation counts from the [OpenAlex API](https://openalex.org) based on each articles's DOI.

## Overview

1. **Data Loading:** Reads tool names and DOIs from a CSV file.
2. **Data Retrieval:** Fetches citation data from OpenAlex for each DOI.
3. **Plotting:** Creates a scatter plot with histograms showing citations by year and total citations for each tool.

## Requirements

Install required packages with:

```bash
pip install requests matplotlib pandas
```

## Usage

1. **Prepare CSV Input:** Create a file (e.g., example.csv) with columns Name and DOI.
2. **Run Notebook:** The script generates and saves a visualization as a .png file.

## Sample CSV

```csv
Name,DOI
Name1,10.1234/example1
Name2,10.5678/example2
```

## Citation
If using this notebook or OpenAlex data, please cite:

Priem, J., Piwowar, H., & Orr, R. (2022). OpenAlex: A fully-open index of scholarly works, authors, venues, institutions, and concepts. ArXiv. https://arxiv.org/abs/2205.01833