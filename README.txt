
##################### MACHINE LEARNING PROJECT SUBMISSON ############


the model is an ensemble of three models each on diffrent set of features to avoid overfitting on private, weghits for models 1 and 2 are 0.7 , 0.3 repectivly,
to produce the same reults run ensembe.ipynb , this file do all the preprocessing for train and test , load the models then produces the result.

to avoid run the preprocessing part run quick_ensemble.ipynb
it will read the cleaned data and produce the result

#NOTE: the preprocessing fills the nulls using catboost regressor which could take some time
on an average machine


## Folder Structure ##

The project follows the following folder structure:

Folder Structure
├── notebooks
│ ├── model#1_Notebook.ipynb
│ ├── model#2_Notebook.ipynb
│ 
├── saved_models
│ ├── model#1
│ ├── model#2
│ 
├── ensemble.ipynb
├── quick_ensemble.ipynb
├── submission_results
│ ├── final_submission.csv
│ ├──Sample_Submission.csv
|
└── cleaned_data
└── cleaned_df.csv

