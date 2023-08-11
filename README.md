# Superstore-Analysis-and-Visualization (numpy - pandas- seaborn ) 
## dashboard using power BI 

![salse](https://github.com/NoorhanHamed/Superstore-EDA-Analysis/assets/113361240/9f5c4372-86d4-4f93-8db6-bc098ba3ec1c)
 #### Introduction
The given code is a Python script that analyzes a dataset called 'Superstore.csv'. The script imports several libraries such as pandas, numpy, and seaborn to perform data analysis, visualization, and manipulation of the dataset. The script provides descriptive statistics, explores the data distribution, and investigates the relationship between various features.

#### Import Libraries
The first few lines of the code imports the necessary libraries required for data analysis and visualization. The libraries used in this script are:
- pandas: for data manipulation and analysis.
- numpy: for numerical operations.
- seaborn: for data visualization.

#### Importing Data
The script imports the dataset 'Superstore.csv' using pandas' read_csv() function. The encoding parameter is used to specify the character encoding of the file.

#### Data Exploration
The script then performs exploratory data analysis (EDA) on the dataset. It provides descriptive statistics using the info() function to show the number of rows, columns and data types in the dataset. The duplicated() function is used to check for duplicated data and sum() function is used to count the number of duplicated rows.

#### Data Cleaning
The script then removes unnecessary columns using the drop() function, which takes the column names and axis=1 as parameters. The inplace parameter is used to modify the existing dataframe instead of creating a new one.

#### Univariate Analysis
The script then performs univariate analysis by exploring the distribution and count of the columns. The countplot() function from the seaborn library is used to visualize the count of unique values in the feature. The value_counts() function is used to count the unique values in the feature. The results are plotted using the countplot() function from the seaborn library.

#### Bivariate / Multivariate Analysis
The script then performs bivariate and multivariate analysis by exploring the relationship between two or more features. The barplot(), heatmap(), and lineplot() functions from the seaborn library are used to visualize the relationship between features. The pivot_table() function from pandas is used to create a summary table.

#### Conclusion
The script provides an in-depth analysis of the 'Superstore.csv' dataset and explores the relationship between various features. It utilizes pandas and seaborn libraries for data analysis and visualization.
