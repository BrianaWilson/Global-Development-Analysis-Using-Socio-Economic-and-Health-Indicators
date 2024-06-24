# Global-Development-Analysis-Using-Socio-Economic-and-Health-Indicators

## Overview

This project aims to group countries based on socio-economic and health factors to determine their development status. The analysis leverages KMeans clustering on data sourced from Help.NGO, an international non-governmental organization specializing in emergency response, preparedness, and risk mitigation.

## Dataset Attributes

country: name of the country
child_mort: death of children under 5 years of age per 1000 live births
exports: exports of goods and services per capita (given as a percentage of the GDP per capita)
health: total health spending per capita (given as a percentage of GDP per capita)
imports: imports of goods and services per capita (given as a percentage of the GDP per capita)
income: net income per person
inflation: the measurement of the annual growth rate of the Total GDP
life_expec: the average number of years a new born child would live if the current mortality patterns remain the same
total_fer: the number of children that would be born to each woman if the current age-fertility rates remains the same
gdpp: the GDP per capita (calculated as the Total GDP divided by the total population)

## Requirements

This project is composed of two files: "Global-Development-Analysis-Using-Socio-Economic-and-Health-Indicators.ipynb" which is the jupyter notebook containing the analysis, and, "Country-data.csv" which is the dataset. 

To run this project, you'll need to install the following libraries: 

- Numpy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

To install the necessary libraries, you can use 'pip'. Run the following command in your terminal:

pip install numpy pandas matplotlib seaborn scikit-learn jupyter

### Usage

Clone this repository to your local machine.
Ensure you have the required libraries installed.
Open the Jupyter Notebook:

jupyter notebook Global_Development_Clustering.ipynb
