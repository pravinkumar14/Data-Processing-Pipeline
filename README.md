# Data-Processing-Pipeline

This notebook employs data pre-processing steps to titanic dataset from Kaggle.

**Kaggle link:** https://www.kaggle.com/datasets/akshaysehgal/titanic-data-for-data-preprocessing

### Description:
Titanic dataset for data exploration, preprocessing and benchmarking basic classification/regression models.

### Columns:
'survived',
'pclass',
'sex',
'age',
'sibsp',
'parch',
'fare',
'embarked',
'class',
'who',
'adult_male',
'deck',
'embark_town',
'alive',
'alone'

### Why data pre-processing?
This is because the raw data collected for modeling is often incomplete, contains outliers, duplicate records, and other inconsistencies. Before building a model, we typically preprocess the data to make it clean, consistent, and ready for analysis, ensuring the model can deliver the best possible results.


## Data Pre-processing pipeline:
1. Check for data summaries
2. Check for de-duplication
3. Check for missing values
4. Feature engineering (Not applicable to this use case)
5. Understand data distribution. (Check for normality, linearity etc.)
6. Check for outliers
7. Train-Test split
8. Feature encoding
9. Check for multi-collinearity
10. Feature selection
11. Check for class imbalance


Following these steps would make the data model ready.

The preprocessing pipeline notebook clearly articulates all the above steps. 

## Steps to run the notebook
1. Create a virtual environment if you're running in a local machine.
2. If run on cloud (colab), skip the above step.
3. Run command "pip install -r requirements.txt"
4. Rull all the cells.
