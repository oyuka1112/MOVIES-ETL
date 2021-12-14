# MOVIES-ETL
- SQL
- ETL
- Python
- Jupyter Notebook
- RegEx
## Overview of the Analysis
Creating a cleaned and ready-to datasets from a web-scrapped messy datasets. Created function, renamed the columns, cleaned the datasets, transformed the datasets, changed the types of the data, and merged and collected the useful ones. 
## Results
- Created movie query into SQL by using wikepedia and kaggle datasets. Transformed and filled missing values
![](https://user-images.githubusercontent.com/64121596/145962850-83542d85-c123-457c-b138-01e2fdba5842.png)
- Created ratings query into SQL using ratings.csv file 
![](https://user-images.githubusercontent.com/64121596/145963027-b4c00d57-277f-444e-8281-63d5749b773a.png)
### Files included:
1. ETL_function_test.ipynb : read wikipedia, kaggle, and ratings files read
2. ETL_clean_wiki_movies.ipynb : extracted, transformed in the way i wanted, cleaned wikipedia movie datasets
3. ETL_clean_kaggle_data.ipynb : extracted, transformed in the way i wanted, cleaned kaggle movie datasets. Created one movie_df dataset that consolidated and cleaned wikipedia and kaggle data.
4. ETL_create_database.ipynb : Additionally, imported the datasets into SQL.
5. Resources: 2 query images that showed 2 tables of movies and rating imported to SQL
