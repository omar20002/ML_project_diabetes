# Machine Learning Project Submission for diabetes dataset using ensemble method

## Project Overview
This project involves creating an ensemble of three models, each trained on a different set of features to avoid overfitting. The weights for models 1 and 2 are 0.7 and 0.3, respectively. 

### Running the Models
1. **Full Processing and Prediction**: 
   - Run `ensemble.ipynb`. This notebook handles all preprocessing for both training and testing, loads the models, and produces the final result.
2. **Quick Prediction**: 
   - Run `quick_ensemble.ipynb`. This notebook reads the cleaned data directly and produces the final result.

**Note**: The preprocessing phase fills null values using a CatBoost regressor, which may take some time on an average machine.

## Folder Structure
The project follows the structure below:



├── notebooks
│   ├── model#1_Notebook.ipynb
│   ├── model#2_Notebook.ipynb
│
├── saved_models
│   ├── model#1
│   ├── model#2
│
├── ensemble.ipynb
├── quick_ensemble.ipynb
├── submission_results
│   ├── final_submission.csv
│   ├── Sample_Submission.csv
│
└── cleaned_data
    └── cleaned_df.csv


## Key Files
- **notebooks**: Contains the Jupyter notebooks for individual models.
- **saved_models**: Directory for saving trained models.
- **ensemble.ipynb**: Main notebook for preprocessing and model ensemble.
- **quick_ensemble.ipynb**: Notebook for quick ensemble without preprocessing.
- **submission_results**: Contains final and sample submission files.
- **cleaned_data**: Directory containing cleaned dataset.

## Instructions for Running the Project
1. Clone the repository.
2. Navigate to the project directory.
3. Run the notebooks as described above.

