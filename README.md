# Thesis Code BAM22
Master Thesis Business Analytics &amp; Management 2022

## Github repository for thesis code
Exludes data, data cleaning and exploration
### Description of each script (ordered by run order):

*  **Data exploration**: Splits training and test sets based on created date and computes summary statistics of each set. 

*  **Phase 1 XGB**: Tunes, trains and tests the performance of the XGBoost model. Feature importance analyses for different feature combinations. 

*  **Phase 2 BMA**: Retrieves manual predictions and tests its performance on the test set. Averages the manual model with XGBoost and tests the performance of the BMA model on the test set. 
 
 *  **Create simulated data**: Modifies original data set to simulated data set, splits a training and test set and computes summary statistics of each set.
 
 *  **Phase 3 Exploration**: Retunes and retraines the XGBoost model on simulated training set, tests performance on simulated test set. New XGBoost model is averaged with the manual lead scoring for a new BMA. Another model is created that excludes the BMA phase. 

 *  **Compare all models**: Compares the performance of all models on the simulated test set based on ROC-AUC, precision, recall, F2, conversion rate and total average opportunity value. 
