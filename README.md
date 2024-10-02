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
## [Project 2: DA Car](/Project_2_Car/Car.ipynb)

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
## [Project 3: DA Police](/Project_3_Police/Police.ipynb)

### Project Usage:
The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* head() - It shows the first N rows in the data (by default, N=5)
* df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.
* df.drop(‘Col_name’ )   - To drop a column from dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* df.groupby(‘Col_1’)[‘Col_2’] .sum( ) - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.
* df['Column_name'].map( { old1:new1 , old2:new2} ) – Change the all values of a column from old to new. We have to write for all values of column otherwise Nan will appear.
* df['Column_name'].mean() - To show Mean value of a column.
* df.groupby('Column_1').Column_2.describe() - To create groups based on Column1 and show statistics summary based on Column2.
### Concentration:

* Q. 1) Instruction ( For Data Cleaning ) - Remove the column that only contains missing values.
* Q. 2) Question ( Based on Filtering + Value Counts ) - For Speeding , were Men or Women stopped more often ? 
* Q. 3) Question ( Groupby ) - Does gender affect who gets searched during a stop ?
Question ( mapping + data-type casting )
* Q. 4) Question ( mapping + data-type casting ) - What is the mean stop_duration ?
* Q. 5) Question ( Groupby , Describe ) - Compare the age distributions for each violation.
---

