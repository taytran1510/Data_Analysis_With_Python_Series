# Data Analysis With Python Series
I have extensive experience in data processing using Python, for example working on a variety of datasets such as weather patterns, car statistics, police reports, COVID-19 data, London housing trends, Udemy courses, and Netflix content. My projects focus on extracting insights through data cleaning, visualization, and statistical analysis using libraries such as Pandas, Matplotlib, Seaborn, and etc. Through these projects, I aim to provide meaningful, data-driven conclusions, emphasizing clear and actionable insights.

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
## [Project 4: DA Covid19](/Project_4_Covid19_Real/Covid19.ipynb)

### Project Usage:
The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* df.count() - It counts the no. of non-null values of each column.
* df.isnull().sum() - It detects the missing values from the dataframe.
* import seaborn as sns - To import the Seaborn library.
* import matplotlib.pyplot as plt - To import the Matplotlib library.
* sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.
* plt.show() - To show the plot.
* df.groupby(‘Col_name’) - To form groups of all unique values of the column.
* df.sort_values(by= ['Col_name'] ) - Sort the entire dataframe by the values of the given column.     
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.
### Concentration:

* Q. 1) Show the number of Confirmed, Deaths and Recovered cases in each Region.
* Q. 2) Remove all the records where the Confirmed Cases is Less Than 10.
* Q. 3) In which Region, maximum number of Confirmed cases were recorded ?
* Q. 4) In which Region, minimum number of Deaths cases were recorded ?
* Q. 5) How many Confirmed, Deaths & Recovered cases were reported from India till 29 April 2020 ?
* Q. 6-A ) Sort the entire data wrt No. of Confirmed cases in ascending order.
* Q. 6-B ) Sort the entire data wrt No. of Recovered cases in descending order.

---
## [Project 5: DA London Housing](/Project_5_London_Housing/London_Housing.ipynb)

### Project Usage:
The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* df.count() - It counts the no. of non-null values of each column.
* df.isnull().sum() - It detects the missing values from the dataframe.
* import seaborn as sns - To import the Seaborn library.
* import matplotlib.pyplot as plt - To import the Matplotlib library.
* sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.
* plt.show() - To show the plot.
* df.dtypes - To show the datatype of each column.
* pd.to_datetime(df.Date_Time_Col) - Converts the data-type of Date-Time Column into datetime[ns] datatype.
* df.Time_Col.dt.year - Creating a new column with only year values
* df.Time_Col.dt.month - Creating a new column with only month values.
* df.insert( index , ‘new_column_name’, new_column_values) - To insert a New column at a particular position with values in it.
* df.drop(['Col_name'] , axis=1 , inplace = True) - To drop a column from the dataframe permanently.
* df.groupby(‘Col_name’) - To form groups of all unique values of the column.
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.
* df.groupby(‘Col_1’)[‘Col_2’] .mean( ) - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.
### Concentration:

* Q. 1) Convert the Datatype of 'Date' column to Date-Time format.
* Q. 2) Add a new column ''year'' in the dataframe, which contains years only.
(2.B) Add a new column ''month'' as 2nd column in the dataframe, which contains month only.
* Q. 3) Remove the columns 'year' and 'month' from the dataframe.
* Q. 4) Show all the records where 'No. of Crimes' is 0. And, how many such records are there ?
* Q. 5) What is the maximum & minimum 'average_price' per year in england ?
* Q. 6) What is the Maximum & Minimum No. of Crimes recorded per area ?
* Q. 7) Show the total count of records of each area, where average price is less than 100000.
---
## [Project 6: DA Udemy](/Project_6_Udemy/Udemy.ipynb)

### Project Usage:
The commands that we used in this project :

* import pandas as pd -- To import Pandas library.
* pd.read_csv - To import the CSV file in Jupyter notebook.
* head() - It shows the first N rows in the data (by default, N=5).
* unique( ) - It shows the all unique values of the column.
* value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.
* df.sort_values(‘Col_name' ,  ascending=False ) - To sort the dataframe wrt any column values in descending order.
* df[ (df.Col1 = = ‘Element1’) & (df.Col2 == ‘Element2’) ] - Multilevel filtering - And Filter – Filtering the data with two & more items.
* str.contains('Value_to_match’) - To find the records that contains a particular string.
* dtypes - To show datatypes of each column.
* pd.to_datetime(df.Date_Time_Col) - To convert the data-type of Date-Time Column into datetime[ns] datatype.
* dt.year - Creating a new column with only year values.
* df.groupby(‘Col_1’)['Col_2'].max() - Using groupby with two different columns.
### Concentration:

* Q. 1) What are all different subjects for which Udemy is offering courses ?
* Q. 2) Which subject has the maximum number of courses.
* Q. 3) Show all the courses which are Free of Cost.
* Q. 4) Show all the courses which are Paid.
* Q. 5) Which are Top Selling Courses ?
* Q. 6) Which are Least Selling Courses ?
* Q. 7) Show all courses of Graphic Design where the price is below 100 ?
* Q. 8) List out all the courses that are related to 'Python'.
* Q. 9) What are courses that were published in the year 2015 ?
* Q. 10) What is the Max. Number of Subscribers for Each Level of courses ?
---
## [Project 7: DA Netflix](/Project_7_Netflix/Netflix.ipynb)

### Project Usage:
The commands that we used in this project :

* head() - It shows the first N rows in the data (by default, N=5).
* tail () - It shows the last N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe.
* size - To show No. of total values(elements) in the dataset.
* columns - To show each Column Name.
* dtypes - To show the data-type of each column.
* info() - To show indexes, columns, data-types of each column, memory at once.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* unique() - It shows the all unique values of the series.
* nunique() - It shows the total no. of unique values in the series.
* duplicated( ) - To check row wise and detect the Duplicate rows.
* isnull( ) - To show where Null value is present.
* dropna( ) - It drops the rows that contains all missing values.
* isin( ) - To show all records including particular elements.
* str.contains( ) - To get all records that contains a given string.
* str.split( ) - It splits a column's string into different columns.
* to_datetime( ) - Converts the data-type of Date-Time Column into datetime[ns] datatype.
* dt.year.value_counts( ) - It counts the occurrence of all individual years in Time column.
* groupby( ) - Groupby is used to split the data into groups based on some criteria.
* sns.countplot(df['Col_name']) - To show the count of all unique values of any column in the form of bar graph.
* max( ), min( ) - It shows the maximum/minimum value of the series.
* mean( ) - It shows the mean value of the series.
### Concentration:


* Task. 1) Is there any Duplicate Record in this dataset ? If yes, then remove the duplicate records.
* Task. 2) Is there any Null Value present in any column ? Show with Heat-map.
* Q. 1) For 'House of Cards', what is the Show Id and Who is the Director of this show ?
* Q. 2) In which year the highest number of the TV Shows & Movies were released ? Show with Bar Graph.
* Q. 3) How many Movies & TV Shows are in the dataset ? Show with Bar Graph.
* Q. 4) Show all the Movies that were released in year 2000.
* Q. 5) Show only the Titles of all TV Shows that were released in India only.
* Q. 6) Show Top 10 Directors, who gave the highest number of TV Shows & Movies to Netflix ?
* Q. 7) Show all the Records, where "Category is Movie and Type is Comedies" or "Country is United Kingdom".
* Q. 8) In how many movies/shows, Tom Cruise was cast ?
* Q. 9) What are the different Ratings defined by Netflix ?
* Q. 9.1) How many Movies got the 'TV-14' rating, in Canada ?
* Q. 9.2) How many TV Shows got the 'R' rating, after year 2018 ?
* Q. 10) What is the maximum duration of a Movie/Show on Netflix ?
* Q. 11) Which individual country has the Highest No. of TV Shows ?
* Q. 12) How can we sort the dataset by Year ?
* Q. 13) Find all the instances where: Category is 'Movie' and Type is 'Dramas' or Category is 'TV Show' & Type is 'Kids' TV'.
---
