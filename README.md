Kenya Agricultural Production Prediction (KAPP)

Project Overview

The Kenya Agricultural Production Prediction (KAPP) project aims to analyse historical agricultural production patterns and develop predictive models for maize production across Kenya's 47 counties.

The project combines agricultural production data, statistical analysis, climate information and machine learning techniques to investigate factors associated with maize production and develop a data-driven prediction system.

Objectives

1. Analyse historical maize production trends across Kenyan counties.
2. Investigate variations in harvested area, production and yield.
3. Integrate relevant climate variables, including rainfall and temperature.
4. Apply statistical methods to investigate relationships between agricultural and climate variables.
5. Develop and evaluate machine learning models for predicting maize production.
6. Build a reproducible agricultural prediction pipeline.

Dataset

The initial agricultural dataset is obtained from the Kenya National Bureau of Statistics (KNBS).

Dataset: Maize Production by County (2012–2020)

- Number of counties: 47
- Observations: 376
- Available years: 2012–2018 and 2020
- Missing year: 2019

Main Variables

- County
- Year
- Harvested area (hectares)
- Production (metric tonnes)
- Yield (metric tonnes per hectare)

Climate variables will be incorporated during subsequent project stages.

Methodology

The project follows these main stages:

1. Data acquisition and understanding.
2. Data cleaning and validation.
3. Climate data acquisition and integration.
4. Exploratory data analysis.
5. Statistical analysis.
6. Feature engineering.
7. Machine learning model development.
8. Model evaluation and comparison.
9. Prediction pipeline development.

Technologies

- Python 3.13
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code
- Git and GitHub

Project Structure

PJ KAPP/
│
├── KAPP/
│   ├── data/
│   │   ├── raw/
│   │   └── processed/
│   ├── notebooks/
│   ├── reports/
│   │   └── figures/
│   └── KAPP_Project.ipynb
│
├── Documentation.ipynb
├── README.md
└── .gitignore

Current Progress

- [x] Initial agricultural dataset acquisition.
- [x] Data cleaning and validation.
- [x] Exploratory data analysis.
- [x] Processed dataset export.
- [x] GitHub repository setup.
- [x] VS Code and Jupyter configuration.
- [ ] Climate data acquisition.
- [ ] Climate and agricultural data integration.
- [ ] Statistical modelling.
- [ ] Machine learning development.
- [ ] Model evaluation.
- [ ] Prediction system development.

Data Source

Kenya National Bureau of Statistics (KNBS).

"Maize Production by County (2012–2020)" (https://nipfn.knbs.or.ke/download/maize-production-by-county-2012-2020/)

Project Status

Status: In Development

This project is an ongoing academic and data science research project.