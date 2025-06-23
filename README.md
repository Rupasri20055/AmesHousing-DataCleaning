# AmesHousing-DataCleaning
Task 1 - Data Cleaning & Preprocessing

About this Task: Hey! So this is my first data cleaning task where I worked on the **Ames Housing dataset** and learned how to clean messy data properly before using it for any ML stuff.

What I did in this task:

1. Imported the **AmesHousing.csv** dataset using Pandas.

2. Explored the data — checked how many columns, what type of data is there, how many nulls, etc.

3. Handled missing values — filled some columns with mean/median and dropped a few columns which had too many nulls.

4. Converted categorical data to numbers — used LabelEncoder and get_dummies wherever needed.

5. Normalized the numerical columns using StandardScaler so everything’s on the same scale.

6. Found outliers using boxplots — mainly in 'GrLivArea' and 'SalePrice' columns.

7. Removed outliers using the IQR method to clean the data better.

8. Finally saved the cleaned data into a new CSV file for later use.

9. Plotted a heatmap to check correlations between different features — helps to know which ones are related.

10. Also checked skewness for 'GrLivArea' and 'SalePrice' to see if any transformation might be needed later.

