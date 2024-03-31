# Chemometrics
This repository contains codes used to develop methodologies to predict the coal quality parameters (ash, moisture, volatile matter, GCV) and classify coal rank from its spectroscopic (VNIR) data. A brief description of the files present in this repository given below:

a) **Coal quality prediction_result-final.ipynb**: This file contains regression methods- SVM, PLS, RF, XGBoost. Input- spectroscopic data of coal in VNIR range. Output - prediction of coal's ash, moisture, volatile matter, and GCV. For more details, please see section 2.3.2. Data modeling of the Journal paper- https://doi.org/10.1016/j.fuel.2020.118676.

b) **Coal rank classification.ipynb:** This file contains classification algorithms- SVM, RF, XGB, Logistic regression to classify different ranks of coal using its spectral properties. Input - spectroscopic data of coal in VNIR (400-2450nm) range. Output - Identifying coal of different ranks. For detailed methodology, please see section 2.3. Data modeling of Journal paper- https://doi.org/10.1016/j.saa.2021.120150  

c)**Excel row.ipynb:** This code is used to convert row to column with a time split of half an hour (48*2n). It is useful for handling the data collected from the Eddy covariance tower, where data is recorded at every 30-minute interval and saved into an Excel file.   


