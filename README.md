## District heating demand prediction with XGBoost
This repository contains the source code of prediction models for district annual energy demand. Typically, the demand quantity is calculated through dynamic simulation software, like TRANSYS and EnergyPlus (Design Builder), utilizing extensive data measurements of the building façade, operational characteristics, and local weather conditions. However, in this project, only 10 measurements were used in the calculation (prediction). Emerging AI technology was also employed in this project, sourcing XGBoost as the base algorithm of the prediction models.
## Structures
Files in this repository are directly divided into two folders (Demand Prediction and Base Temperature Prediction), coincide with the prediction approaches in the project. Each folder contains:
-	Algorithm training code, including post-training data analysis
-	Algorithm testing code, including post-testing data analysis 
-	Exported pre-trained models from 5 different training datasets (6000 cases each)

All of the codes were scripted in Python 3.10, deployed in Anaconda environment.
## Reports and Publications
The development of this project is included in the following publications:

Paper 1: Ranking building design and operation parameters for residential heating demand forecasting with machine learning ([source](https://doi.org/10.1016/j.jobe.2024.108817))

Associated research data: ([source](https://data.mendeley.com/datasets/pybn6gb2m6/2))
