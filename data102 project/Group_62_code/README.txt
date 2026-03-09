# Group 62

The code for our project is separated between 4 notebooks, all of which are in this folder. All data and image files used in those notebooks are also in this folder. This file is a description of each notebook, along with which of the files must be imported into the session for each notebook to ensure a smooth execution of the code cells.

# Notebooks

## EDA.ipynb
This is the notebook used for our exploratory data analysis (EDA), and for submission to the first checkpoint of this project. The following files should be imported into the session when running this notebook:
- `clean_data.csv`

## Q1.ipynb
This is the notebook used for the exploration and analysis pertaining to our Research Question 1, as described by the Method and Results subsections in our report. There is some overlap with the EDA notebook since some of the variables, methods, and graphs were reused for continuity. The following files should be imported into the session when running this notebook:
- `clean_data.csv`
- `dag_final.png`

## GLM.ipynb
This is the notebook used for developing, training, and assessing the generalized linear models (GLMs) used for our Research Question 2. The following files should be imported into the session when running this notebook:
- `clean_data.csv`
- `test.xlsx`

## Random_Forest.ipynb
This is the notebook used for developing, training, and assessing the random forests used for our Research Question 2. The following files should be imported into the session when running this notebook:
- `clean_data.csv`
- `test.xlsx`

# Files

## clean_data.csv
This CSV file is a merge between the datasets mentioned in our report, filtered such that it only contains data from California in 2018 for specificity and lower volume. It is also filtered such that the only chronic illness contained in the data is asthma, since that is the only one our experiment referred to.

## dag_final.png
This directed acyclic graph (DAG) illustrates the causal relationship between all variables (treatment, outcome, and confounders) in the experiment performed for our Research Question 1.

## test.xlsx
This is the testing data used to evaluate the performance of the GLMs and random forests used in the experiments pertaining to our Research Question 2.