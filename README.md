Getting started:  
Step 1: Unzip "application_train.rar" and get data  
Step 2: Install Anaconda and run "Prediction.ipynb" using Jupyter Notebook.  
Introduction:  
Pandas has been used to extract data from Excel and all columns have been listed in ascending order of missing values. All non-numeral columns have been encoded with LabelEncoder. Exploratory data analysis (EDA) was performed on columns that are not linear with the target value and their correlations with the target value have been illustrated with kdeplot and heatmap. Missing values were filled in with SimpleImputer to combine some of the currently resulting features with the population. Data was preprocessed with Standard Scaler, MinMaxScaler. Models such as logic regression, random forests and LightGBM were useed to train the model.  
