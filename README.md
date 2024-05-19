# Customer-Call-List---Data-Cleaning-in-Pandas-
Standardizing data consisting of multiple and different types of anomalies using Pandas in Jupyter Notebook 

This DataSet is small. So, we can go through data manually to identify non standard data.
# Step-1 
We convert the raw data to Data Frame using Pandas 
# Step-2
Here, we drop all the columns which are duplicates of each other.
# Step-3
Now, we standardize data by going column by column.
## First ## 
We strip all the non alphabets in the column "Last_Name".
## Second ##
We replace all the characters except required with empty string in the column "Phone_Number".
And now we format all the values in the column "Phone_Number".
## Third ##
We split the "Address" column into 3 other columns.
## Fourth ##
Now, we format the columns "Paying Customer" and "Do_Not_Contact" by replacing the values with either Y or N instead of others.
# Step-4
And the null values that we checked in the beginning are cleaned here by replacing Null values with an empty string.
Alongside, we drop the columns which we analyzed and deem as not required.
## Step-5
Finally, we reset the Index properly.

