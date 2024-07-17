
# Sales data Analysis using PANDAS

## Setup
To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html.  
Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html

## About
In this project, I worked with a real-world electronics dataset, leveraging various Python libraries to extract, analyze, and visualize data. The primary tools and libraries used include:

Pandas: For data manipulation and analysis.  
Numpy: For numerical operations and array manipulations.
Matplotlib: For creating static visualizations.  
Seaborn: For statistical data visualization.  
os: For interacting with the operating system to manage files and directories.  

In this Project we use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

We start by Installing the libraries.



## Deployment

We start by Importing the libraries.

```bash
  import numpy as np
  import pandas as pd
  import matplotlib.pyplot as plt
  %matplotlib inline
  import seaborn as sns
  import os
```
## Cleaning Data

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

## Tasks:-
Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 4 high level business questions related to our data:

**Q.** What was the best month for sales? How much was earned that month?  
**Q.** What city sold the most product?  
**Q.** What time should we display advertisemens to maximize the likelihood of customer’s buying product?  
**Q.** What products are most often sold together?

## Solution:-
To answer these questions we walk through many different pandas & matplotlib methods. They include:

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
 