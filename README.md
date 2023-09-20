#### This is the README for Group 7 of STATS 170. This project is trying to predict and analyze Credit Card Default Rates using Survival Analysis and other methods.

Created by Ethan So, Michael Chong, Rex Kim, Yoon Kim, and William Chiang

#### This repository contains the following files:

Main scripts used for the whole project:  

preprocessing.Rmd:  Preprocesses the dataset to get it ready for modeling. Requires downloading the application_record.csv and the credit_record.csv file from [Kaggle](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction?resource=download). Outputs a new csv file of the merged data.  
eda.ipynb:  Exploratory data analysis  
classification_models.ipynb:  Builds the logistic regression classifier  
survival_models.Rmd:  Builds the Kaplan-Meier and Cox Proportional Hazards models  
project.Rmd:  Demonstration of the project  

Data files:  
data.csv:  the merged data file created from preprocessing.Rmd  
data_as_numerical.csv:  data.csv but datatypes converted to numerical for model building  

#### To run the demonstration of the project:
1. Download the data.csv file and project.Rmd file.  
2. Place both files in the same location.  
3. Run the R Markdown project.Rmd file.  
