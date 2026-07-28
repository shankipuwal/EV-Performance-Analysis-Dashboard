# EV Performance Analysis Dashboard

[![License](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)

One-line summary
A Power BI dashboard and supporting Python notebooks for exploratory analysis and performance insights on electric vehicles (EVs). This repository contains the dataset, visual assets, a Power BI report (.pbix), and the notebooks used for data profiling and feature engineering.

Table of contents
- [Project overview](#project-overview)
- [Quick demo / screenshots](#quick-demo--screenshots)
- [Repository structure](#repository-structure)
- [Dataset](#dataset)
- [How to open the Power BI report](#how-to-open-the-power-bi-report)
- [How to run the Python notebooks](#how-to-run-the-python-notebooks)
- [Requirements & installation](#requirements--installation)
- [Suggested improvements & notes](#suggested-improvements--notes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

Project overview
This project analyzes EV performance across multiple dimensions (efficiency, charging behavior, geographic energy insights) and presents an interactive Power BI dashboard for stakeholders. The Python notebooks document the data profiling and feature engineering steps used to prepare the dataset.

Quick demo / screenshots
Preview images are stored in the `Images/` folder. Open `Images/Dashboard_Overview.pdf` for a printable overview. Example image files:
- `Images/Executive Overview.JPG`
- `Images/EV Efficiency Analytics.JPG`
- `Images/Charging & Range Analytics.JPG`

Repository structure
- Dataset/
  - ev_final_dashboard_dataset.csv
- Images/
  - Charging & Range Analytics.JPG
  - EV Efficiency Analytics.JPG
  - Geographic Energy Insights.JPG
  - Executive Overview.JPG
  - Numerical Distribution.JPG
  - Dashboard_Overview.pdf
- PowerBI/
  - EV Performance Analysis Dashboard.pbix
- Python/
  - ADVANCED BUSINESS ANALYTICS.ipynb
  - EV PROJECT — DATA PROFILING.ipynb
  - FEATURE ENGINEERING.ipynb
- requirements.txt
- LICENSE
- README.md

Note: I corrected the spelling "Georaphic" → "Geographic" in the list above; if the filename in your repo is spelled differently, consider renaming it (or update the README to match exactly).

Dataset
File: `Dataset/ev_final_dashboard_dataset.csv`

Please add a data dictionary (suggested file: `Dataset/DATA_DICTIONARY.md`) that describes:
- Column name
- Type (numeric / categorical / datetime)
- Description and units (if applicable)
- Example values or allowed ranges

Quick preview (run locally)
```python
import pandas as pd
df = pd.read_csv("Dataset/ev_final_dashboard_dataset.csv")
print(df.shape)
df.head()
df.info()
└── LICENSE
