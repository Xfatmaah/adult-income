# adult-income - Analysis
Preprocessing & EDA for the Adult census income

# Notebook contains:
1. Perform data cleaning
    * " replace '?' while reading the data "
2. Display top 5 rows
3. Display last 5 rows
4. Show dataset shape
5. Getting information about dataset
    * " df.info() "
6. Fetch random sample (50%)
7. Check duplicated data & drop them
8. Check null valus
9. Fill null valus with mode ' more valuable duplicate '
10. Drop columns that represent same data
    * " education & education.num represent same data, so I dropped education column "
11. Encode 'income' column
    * " <=50K : 0,  >50K : 1 "
12. Show correlation matrix
13. Drop non-related data
14. Get overall statistics about Dataframe
    * " df.description() "
15. Handel outliers
16. Display categorical data info
    * " df.describe(include = ['object']) "
17. Total number of person having age between (17,48)
18. Which workclass getting the highest salary?
19. Which workclass working more hours?
20. How many persons having Bachelors & Master Degree?
21. convert workclass column datatype to category

### Data visualizing:
1. The distribution of age column
2. How many people get paid '<=50K' & '>50K'?
3. Who has better chance to get salary '>50K' & '<=50' Male or Female?
4. Which workclass has better chance to get salary '>50K' & '<=50'?
5. Show how many hours per week each age group works
