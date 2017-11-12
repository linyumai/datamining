# datamining
Data Mining Project for the Zillow Kaggle Competition <br />
Special thanks to Kaggle https://www.kaggle.com/c/zillow-prize-1 for the opportunity to both learn and apply more data mining skills.<br /> 
Credits/links to public kernels used to benchmark our scores can be found in the report.<br />
All codes were run with Python 3.6. <br />
As stated in the report, we had to redesign the competition training and testing set as the submission deadline was over
test.csv, train.csv and new_submission.csv are the files we used for testing, training and submitting data respectively. <br />
In addition, the new algorithm to derive the average MAE score as described in the report is found in the models' files themselves. <br />
An example can be found in Score calculator (LightGBM benchmark).ipynb <br />

# Note
Please ensure that you have the related dependencies installed before running the models. <br />
Some of the models may require hours to complete, such as our CatBoost Our Best Model.ipynb <br />

# Model : Filename
CatBoost Benchmark : CatBoost_BenchMark.ipynb <br />
CatBoost top score : CatBoost Our Best Model.ipynb <br />
LightGBM Benchmark : Benchmark LightGBM.ipynb <br />
LightGBM tuned     : LightGBM tuned and cleaned data.ipynb <br />
XGB                : XGB.ipynb <br />
Random Forest      : RandomForestRegressor - OneHotEncoding.ipynb <br />



# Instructions: 
Data preprocessing - There are 2 files for data preprocessing, Submission - Data Cleaning.ipynb and Submission - Data Cleaning - CAT.ipynb
<br />
As the properties file is too large to upload, these files have to be run to save the preprocessed data in your local workspace. (you would need to download the original properties_2017.csv file from kaggle<br />
The files will generate the properties file into a csv format, where you can rename them at the bottom cell of the ipynb file.
Depending on the model, it uses the non-CAT version unless you are trying to run the CatBoost. <br />
For each model, the only changes that have to be done is to link the needed files paths in the first few cells of the ipynb file. <br />
Run the model to completion on the ipynb file ( Shift + enter ) <br />


