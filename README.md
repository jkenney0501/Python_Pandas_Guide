# Python Pandas Guide
![Pandas Image](Pandas_logo.svg.png)

A simple guide with examples for working with Pandas. This series will expand in the future to include more examples of functions applied to data frames but for now it's a good basic guide to using Pandas for data analysis. Explanations are not real deep, it's for my reference but anyone is welcome to use it, clone it or do whatever you want with it. I will be updating as I go.

## Understanding the Pandas Series
- [Series Intro](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Series.ipynb)
  - Creating a Series from a list, dictionary and csv
  - Attributes
  - Methods
  - Parameters and arguements
  - Sorting by value and index
  - Extracting by label and index position
  - Using apply method with custom functions
  - Using the map method

## Data Frames
- [Intro](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_1_A_intro_select_insert.ipynb)
  - Selecting, Assigning new columns and using insert.

- [Data Cleaning (Basic Null value handling)](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data%20Preparation%20-%20Working%20with%20Missing%20Values%20in%20Pandas.ipynb)
  - Dealing with Nulls, NaN using isna( )
  - Replacing with fillna( )
  - Changing parameters

- [Operations, dropping and filling NA's & Conerting data types](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_1_B_ops_counts_na_astype.ipynb)

- [Sorting and Ranking](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_1_C_Sorting_Ranking.ipynb)

- [Filtering and Cleaning Data](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_2_Filtering_Data.ipynb)

- [Data Extraction pt1](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_3_Data_Extraction.ipynb)
  - Setting the index, using .loc and .iloc

- [Data Extraction pt2](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_3_Data_Extraction_Samples_Where_Apply_funcs.ipynb)
  - Random Samples
  - nlargest/smallest method
  - using the where( ) method
  - using the apply( ) method with a function for rows and columns

- [Group By](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_6_Group_By.ipynb)

- [Working with Dates & Times](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_8_Dates_Times.ipynb)
  - Python date/time module
  - Timestamps
  - Pandas to_datetime method
  - Handling errors
  - Time delta Object

- [Example of grouping and using a max date value](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/DataFrames-Sorting%20loans%20in%20a%20group%20and%20taking%20the%20most%20recent%20date.ipynb)
  - Time delta is also applied to create new columns based on a date

- [Merge, Join & Concatenate DataFrames](http://localhost:8888/notebooks/OneDrive/%C3%81rea%20de%20Trabalho/Python-%20A_Pandas_Guide/Notebooks/Merge%2C%20Join%20%26%20Concatenate%20DataFrames.ipynb)
  - Concatenating
  - Joins - inner, outer, left
  - Join paramters
  - Merging
 

- [Working with Text Data](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Data_Frames_Working_with_Text_Data.ipynb)
  - Common methods - lower, upper, title and lrn
  - Replacing values in a string
  - Strip, lstrip, rstrip
  - Spliting strings


## Data Visualization 
- [Visualization with Pandas](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Visualization%20in%20Pandas.ipynb)
  - Basic Pandas charts and graphs for quick use
  - Time Series, bar, scatter (Unfinished for now)
  - Modifying aesthetics

- [Matplotlib Basic Visualizations](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Visualization-Line-Freq-Hist-Box-Pie-scatter.ipynb)
  - Basic bar, line, hist, scatter plots.
  - Sub plots, multiple plots

- [More Matplotlib - Modern and Most Complete Version](https://github.com/jkenney0501/Python_Pandas_Guide/blob/main/Notebooks/Matplotlib%20Guide.ipynb)
  - Additional customization for plots - This is the most technical version with a lot of details for plots and styling.
