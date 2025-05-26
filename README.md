# Group Project          # Creates a README file
"# group-project" 
# Employer Project – LSE Data Analytics- 
# Team 12- Bank of England 

This project analyzes the impact of Bank of England speeches on economic indicators using sentiment analysis and regression models.

## Contents
# Notebooks and Files
- `BankSpeeches_StarterCode-10.ipynb`: Data cleaning and validation, Sentiment Analysis, Bank Rate Changes, Merging (economical indicators with finbert sentiment), correlation matrices
- `Correlation Matrices and Timeframes with Key Event/`:
- `Speech Analysis/`: Top Positive/Negative Speech Analysis, Top Author and Word Analysis
- `report_publication_dates/`: Cleaned MPR and FSR Publication Dates (.csv) files and timeframe graph including both
- `cleaned_economic_data/`: Cleaned economical indicators (.csv)
- `Checked analysis files/`: Graphs for each dependant variable with key events, MPR and FSR Dates, Correlation Matrices with time lags, Pairplots, Regression Models for CPI, GDP, Unemployment Rate, Bank Rate, Confidence Score, Wage Growth Rate for each timeframes
- `Further Analysis (Copies)/`: Regression models with adding (replacing lagged version dependent variable with) sentiment score as independent variable, scatter plots sentiment scores vs. dependant variable for each timeframes
- `merged_sentiment_copy.csv`: Merged file (economical indicators + finbert sentiment score)
- `df_uk_for_top_speeches.csv`: All BOE tokenized speeches with all sentiment analysis scores

## How to Reproduce
## Setup and Reproducibility
To reproduce this project and run the notebooks locally, follow the steps below:
# 1. Clone the Repository
```bash
git clone https://github.com/gamzebb/group-project.git
cd group-project
# 2. Install All Dependencies
pip install -r requirements.txt
# 2. Run (ex.) `BankSpeeches_StarterCode-10.ipynb` in Jupyter

## Authors
- Gamze Bozkurt Omar
- Justin Low
- Elif Ozkol
- Aoife-ni-Mhorain
- Emily-Tang
