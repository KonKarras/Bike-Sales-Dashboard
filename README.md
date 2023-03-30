# Bike Sales Dashboard

Project aimed for cleaning and analyzing the dataset found in the BikeSalesDataset.xlsx file, which contains information (1026 rows and 13 columns) regarding global bike sales. In particular, the first 12 columns mainly include demographic data, while the last column indicates whether the respective individuals actually purchased a bike or not.

After importing the file in Excel, we start by creating 3 new sheets:

1) the "Working" sheet: a copy of the original data where we can perform all the cleaning procedures, without worrying about transforming or even losing our raw table,

2) the "Pivot Tables" sheet: where we insert the features we want to analyze and derive insights from and finally

3) the "Dashboard" sheet: where we insert the visualizations of our analysis as well as the filters by which we group our entries.

More precisely, the cleaning process results in 1000 rows (that means a table only 0.025% smaller than the original one) and consists of:

a) removing duplicates,

b) replacing values with more meaningful entries (eg: M with Married in the "MaritalStatus" column, F with Female in the "Gender" column, etc.)

c) transforming the "Income" column to currency data type and

d) splitting the "Age" column into 3 different intervals.

Continuing with the analysis of the dataset, we create 3 pivot tables where we concentrate on:

a) the average "Income" against the "Gender",

b) the Count of People against every "Commute Distance" interval and

c) the Count of People against every "Age" interval.

On every one of those tables, we also apply the binary division (Yes or No) of the "Bike Purchased" column, so that we gain a better perspective over the dataset's features.

Lastly, we build our dashboard by simply creating, customizing and inserting the plots of every respective pivot table, added with 4 "Slicers", a function which allows us to interact with our visualizations and filter them by "Region", "Marital Status", "Cars" and "Education".

The final result can be accessed through the BikeSalesDashboard.xlsx file.
