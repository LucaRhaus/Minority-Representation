**Repository for a term paper project on minority representation in democracies. Written in R-Quarto.**

## 1. Setup

The project is written in R-Quarto - a Notebook-Style Version of R, similar to Jupyternotebooks in Python. To be able to run the scripts, make sure your IDE supports Quarto. 

Before running the project you have to set the variable "rootpath" to your local working directory, where your scripts are located.

## 2. Structure

This repository provides all the data (minorities_data.xlsx) you need to run the script "data analysis.qmd". 

The script "case selection and data preparation.qmd" transforms and combines the raw data from various sources (see "3. Datasets") into one xlsx file "minorities_data.xlsx".

## 3. Datasets

- Ethnic Power Relations (EPR): Group & Country level
- VDEM v14 (loaded via R Package 'vdemdata')
- IPU Parline (using the online API)
- Manually collected data that can be found in "collected_party_data.xlsx"

NOTE: The VDEM R Package always loads data from the most recent Version of VDEM. When trying to reproduce the results in the dataset "minority_data.xlsx" you might want to check your version of VDEM. While this applies to IPU Parline as well, it should not cause any problems since the IPU data is hard coded in the manually edited xlsx file "collected_party_data.xlsx"
