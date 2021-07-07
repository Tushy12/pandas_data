# pandas_data
Here,
Set of real world data science tasks completed using the Python Pandas library.

### Setup
You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html

Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html

#### Background Information:

In this repo we use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

We start by cleaning our data. Tasks during this section include:

Drop NaN values from DataFrame
Removing rows based on a condition
Change the type of columns (to_numeric, to_datetime, astype)
Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:

1) What was the best month for sales? How much was earned that month?
2) What city sold the most product?
3) What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4) What products are most often sold together?
5) What product sold the most? Why?

To answer these questions we walk through many different pandas & matplotlib methods. They include:

Import data from CSV files using-
  i) .read_csv()
  ii) Use os.path.join() if you want freedom from the type of Operating System.
Concatenating multiple csvs together to create a new DataFrame (pd.concat)
Using groupby to perform aggregate analysis
Plotting bar charts and lines graphs to visualize our results
Labeling our graphs
