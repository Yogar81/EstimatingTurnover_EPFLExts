# Estimating Turnover in Retail trade
## Capstone project for the program "Advanced Data Science: Machine Learning" of the EPFL Extension School

The Retail Trade Turnover Statistics (DHU) is a monthly economic statistic by the Federal Statistical Office (FSO) describing the evolution of turnover in retail trade at the national level. The survey population comprises all enterprises active in retail trade which are domiciled in Switzerland. Large and medium enterprises are surveyed exhaustively, small enterprises are surveyed randomly. The sample consists of around 4000 enterprises. Large enterprises are surveyed each month, the others four times per year, when monthly data are collected. To be able to publish representative results every month, data for three months are collected with one questionnaire for small and medium enterprises, but shifted by zero, one or two month for the three sub-samples. More information can be found on the FSO website: www.dhu.bfs.admin.ch

### Goal of this project
At the time of the calculation of the results, not all enterprises have responded to the survey. Furthermore, the data users wish first estimations even earlier. Therefore, the goal of this project is to find methods to estimate the turnover of a given enterprise for a given month by using the information available from other respondents and the past.

### Organisation
This project is split in 3 parts:
* Data Preparation
* Data Exploration
* Machine Learning


In the Machine Learning part, 4 models are tested and tuned:
* Ridge Regression
* kNN Regression
* RandomForest Regression
* Clustering (k-Means)


The project contains the following jupyter notebooks:
* 1_DataPreparation
* 2_DataExploration
* 3.1_ML_Preparation
* 3.2_ML_Ridge
* 3.3_ML_kNN
* 3.4_ML_RandomForest
* 3.5_ML_Clustering
* 3.6_ML_Results
