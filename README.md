# Predicting Patient Readmission

A comprehensive project focused on analyzing and predicting 30-day hospital readmission rates. This repository includes cleaned datasets, data wrangling notebooks, exploratory data analysis, mediation analysis, and machine learning models for predictive insights.

The project aims to understand factors influencing hospital readmission rates, leveraging mediation analysis and machine learning models to uncover actionable insights. Data from multiple sources such as income, population, and readmission rates are used to explore relationships and predict outcomes.

## Key Questions:
What socio-economic factors contribute to 30-day readmission rates?<br/>
Does income mediate the relationship between population and readmission rates?<br/>
How can machine learning models improve the prediction of readmission rates?<br/>

## Repository Structure

``` plaintext

├── datasets/
│   ├── CalHHS_30-Day_Readmission_Rate.csv
│   ├── Cal_County_Pop_2011-2022.csv
│   ├── County_Pop_Income_RR.csv
│   ├── County_RR_By_Income.csv
│   ├── PCPI_California_2011_2022.csv
│   └── primary.csv
│
├── notebooks/
│   ├── Data_Wrangling/
│   │   ├── Avg_Income_By_County_Cal.ipynb
│   │   ├── CalHHS_30-Day_Hospital_Readmission_Rate.ipynb
│   │   ├── Cal_County_Pop_2011-2022.ipynb
│   │   ├── County_Pop_Income_RR.ipynb
│   │   └── County_RR_By_Income.ipynb
│   │
│   ├── Analysis/
│       ├── Exploratory_Data_Analysis_1.ipynb
│       ├── Exploratory_Data_Analysis_2.ipynb
│       ├── Mediation_Analysis.ipynb
│       └── Model_Selection.ipynb
│
├── requirements.txt
└── README.md
```
## Features

Data Wrangling: Preprocesses datasets to ensure consistency and usability.<br/>
Exploratory Data Analysis (EDA): Visualizes patterns and trends in readmission rates, income, and population data.<br/>
Mediation Analysis: Explores relationships between income, population, and readmission rates.<br/>
Machine Learning: Implements predictive models to identify factors most impacting readmission rates.<br/>
Installation

## Prerequisites:
Python (3.8 or higher)
Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn, PyCaret<br/>
Steps:
### Clone this repository:
```bash
git clone https://github.com/username/Predicting_Patient_Readmission.git
```

### Navigate to the project directory:
``` bash
cd Predicting_Patient_Readmission
```
### Create and activate a virtual environment:
``` bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```
### Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Data Wrangling:
Run the notebooks in the Data_Wrangling folder to clean and preprocess the data:

``` bash
notebooks/Data_Wrangling/Cal_County_Pop_2011-2022.ipynb
```

### Analysis:
Start with Exploratory_Data_Analysis_1.ipynb and Exploratory_Data_Analysis_2.ipynb for visual insights.<br/>
Use Mediation_Analysis.ipynb to explore relationships between variables.<br/>
Apply machine learning models with Model_Selection.ipynb.<br/>

## Results

### Key Findings:
Mediation analysis shows limited evidence for income acting as a mediator between population and readmission rates.<br/>
Machine learning identified significant features such as population size and admission proportions.<br/>
Model Performance:<br/>
R-squared: 0.77 for Gradient Boosting Regressor model predicting readmission rates.<br/>

## Contributing

I welcome contributions to improve the project! Please follow these steps:

Fork this repository.
Create a new branch:
Commit your changes:
```bash
git commit -m "Add new feature"
```
Push the changes and open a pull request.
Refer to the Contributing Guidelines for more details.

## License

This project is licensed under the MIT License.

## Acknowledgments

Statistical Models: Thanks to Statsmodels.<br/>
Visualization: Built using Matplotlib and Seaborn.<br/>
Data Sources: Datasets curated from public California HHS and population statistics.<br/>
This product uses the FRED® API but is not endorsed or certified by the Federal Reserve Bank of St. Louis.<br/>
