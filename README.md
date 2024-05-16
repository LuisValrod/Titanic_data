# Titanic data exercise
### Steps
- #### Load the titanic dataset using seaborn:
  - pip install seaborn, 
  - 'import seaborn as sns'
  - load using 'sns.load_dataset('titanic')'
- #### Clean the dataset: 
  - Where are the missing values? 
  - Can they be filled/need to be dropped?: 
    - df.isnull() 
    - df.fillna()
    - df.dropna()
  - Are there any duplicates?: 
    - df.duplicated()
    - df.drop_duplicates()
  - Do any columns need renaming? 
    - df.rename()
  - Any other data quality concepts you can check?
- #### Check the descriptive statistics 
  - df.describe()
- #### Find the average fare and age for each class 
  - df.groupby()
  - mean()
- #### Add a new column showing the fare as a percentage of total
  - How many survivors were female compared to male?

- #### What interesting insights can you draw?