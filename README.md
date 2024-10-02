# Data Analysis With Python Series
Welcome to my personal Power BI portfolio repository! Here you will find a collection of Power BI projects and dashboards that demonstrate my skills and expertise in data visualization, business intelligence, and analytics using Power BI.

---
## [Project 1: DA Weather](/Project_1_Weather/Weather.ipynb)

### Project Usage:
The commands that I used in this project :

* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.
### Concentration:
* Q. 1)  Find all the unique 'Wind Speed' values in the data.
* Q. 2) Find the number of times when the 'Weather is exactly Clear'.
* Q. 3) Find the number of times when the 'Wind Speed was exactly 4 km/h'.
* Q. 4) Find out all the Null Values in the data.
* Q. 5) Rename the column name 'Weather' of the dataframe to 'Weather Condition'.
* Q. 6) What is the mean 'Visibility' ?
* Q. 7) What is the Standard Deviation of 'Pressure'  in this data?
* Q. 8) What is the Variance of 'Relative Humidity' in this data ?
* Q. 9) Find all instances when 'Snow' was recorded.
* Q. 10) Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.
* Q. 11) What is the Mean value of each column against each 'Weather Condition ?
* Q. 12) What is the Minimum & Maximum value of each column against each 'Weather Condition ?
* Q. 13) Show all the Records where Weather Condition is Fog.
Q. 14) Find all instances when 'Weather is Clear' or 'Visibility is above 40'.
Q. 15) Find all instances when :
A. 'Weather is Clear' and 'Relative Humidity is greater than 50'
or
B. 'Visibility is above 40'
---
---
## [Project 2: DA Car](/Project_1_Car/Car.ipynb)

### Project Usage:
The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* head() - It shows the first N rows in the data (by default, N=5)
* shape - It shows the total no. of rows and no. of columns of the dataframe
* df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.
* fillna() - To fill the null values of a column with some particular value
* value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.
* isin() - To show all records including particular elements
* apply() - To apply a function along any axis of DF
### Concentration:
* Q. 1) Instruction ( For Data Cleaning ) - Find all Null Values in the dataset. If there is any null value in any column, then fill it with the mean of that column.
* Q. 2) Question ( Based on Value Counts )- Check what are the different types of Make are there in our dataset. And, what is the count (occurrence) of each Make in the data ?
* Q. 3) Instruction ( Filtering ) - Show all the records where Origin is Asia or Europe.
* Q. 4) Instruction ( Removing unwanted records ) - Remove all the records (rows) where Weight is above 4000.
* Q. 5) Instruction ( Applying function on a column ) - Increase all the values of 'MPG_City' column by 3.
---


