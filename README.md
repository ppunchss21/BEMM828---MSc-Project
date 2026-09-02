# MSc Project – Net-Zero Transition Disclosure Credibility

## Project Overview
This repository contains the data, methodology files, Python notebook, and analytical outputs used for the MSc Business Analytics project:

**Achieving Net Zero While Maintaining Financial Performance: An Empirical Analysis of Net-Zero Transition Disclosure Credibility and Financial Performance among Thai Listed Companies**

The study develops a Net-Zero Transition Disclosure Credibility Index (NZTDCI) for selected Thai listed companies from 2022–2025 and examines its association with accounting-based financial performance.

## Repository Structure

### `data/`
Contains the final datasets used in the analysis.

- `NZTDCI pre regression combine.xlsx` – final consolidated coding and financial dataset.
- `17_regression_data_used.csv` – final 60 company-year observations used in the regression analysis.
- `source_document_register.xlsx` – register of corporate source documents and official source links.
- `source_financial_files/` – underlying financial data files used to construct the analytical variables.

### `methodology/`
Contains supporting files for the structured coding process and blind second-pass coding exercise.

Earlier Python V1 and V2 rule-based analyses were used as computational robustness and evidence-retrieval checks. They were not used as the final disclosure coder.

### `notebooks/`
- `NZTDCI_Final_Analysis.ipynb` – Jupyter notebook containing the coding checks, data preparation, descriptive analysis, regression models, robustness analysis, diagnostics, and output generation.

### `outputs/`
Contains the analytical outputs produced during the study, including:

- descriptive and regression tables
- diagnostic results
- dissertation figures
- full statistical software output

## Source Documents
The study used publicly available annual reports, Form 56-1 One Reports, sustainability reports, climate-related reports, and official company sources.

Original corporate PDF reports are not redistributed in this repository because of file-size and copyright considerations. Source details and official URLs are provided in `data/source_document_register.xlsx`.

## Reproducibility
The final regression analysis is based on the consolidated final dataset and the 60-observation regression dataset retained in the `data/` folder. Supporting analytical outputs are provided in the `outputs/` folder to allow the reported results to be traced and checked.
