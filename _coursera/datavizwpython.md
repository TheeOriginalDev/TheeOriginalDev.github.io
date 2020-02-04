---
title: "Data Visualization With Python"
excerpt: "Take a trip with me while I learn about data visualization and some of the best practices to keep in mind when creating plots and visuals. I will be learning about area plots, histograms, bar charts, pie charts, box plots, scatter plots and bubble plots and how to create them with Matplotlib. I will also be learning about advanced visualization tools such as waffle charts and word clouds, seaborn, which is another visualization library, and how to use it to generate attractive regression plots. In addition, I will also learn about Folium, which is another visualization library, designed especially for visualizing geospatial data. Lastly I will display how to use Folium to create maps of different regions of the world, how to superimpose markers on top of a map, and how to create choropleth maps."
---

# Exploring Datasets with *pandas* <a id="0"></a>

*pandas* is an essential data analysis toolkit for Python. From their [website](http://pandas.pydata.org/):
>*pandas* is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, **real world** data analysis in Python.

The course heavily relies on *pandas* for data wrangling, analysis, and visualization. We encourage you to spend some time and  familizare yourself with the *pandas* API Reference: http://pandas.pydata.org/pandas-docs/stable/api.html.

## The Dataset: Immigration to Canada from 1980 to 2013 <a id="2"></a>

Dataset Source: [International migration flows to and from selected countries - The 2015 revision](http://www.un.org/en/development/desa/population/migration/data/empirical2/migrationflows.shtml).

The dataset contains annual data on the flows of international immigrants as recorded by the countries of destination. The data presents both inflows and outflows according to the place of birth, citizenship or place of previous / next residence both for foreigners and nationals. The current version presents data pertaining to 45 countries.

In this lab, we will focus on the Canadian immigration data.

For sake of simplicity, Canada's immigration data has been extracted and uploaded to one of IBM servers. You can fetch the data from [here](https://ibm.box.com/shared/static/lw190pt9zpy5bd1ptyg2aw15awomz9pu.xlsx).

---
## *pandas* Basics<a id="4"></a>
The first thing we'll do is import two key data analysis modules: *pandas* and **Numpy**.

```python
import numpy as np  # useful for many scientific computing in Python
import pandas as pd # primary data structure library
```

Let's download and import our primary Canadian Immigration dataset using *pandas* `read_excel()` method. Normally, before we can do that, we would need to download a module which *pandas* requires to read in excel files. This module is **xlrd**. For your convenience, we have pre-installed this module, so you would not have to worry about that. Otherwise, you would need to run the following line of code to install the **xlrd** module:
```python
!conda install -c anaconda xlrd --yes
```

Now we are ready to read in our data.

```python
!conda install -c anaconda xlrd --yes

df_can = pd.read_excel('https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DV0101EN/labs/Data_Files/Canada.xlsx',
                       sheet_name='Canada by Citizenship',
                       skiprows=range(20),
                       skipfooter=2)

print ('Data read into a pandas dataframe!')
```

Let's view the top 5 rows of the dataset using the `head()` function.

```python
df_can.head() # tip: You can specify the number of rows you'd like to see as follows: df_can.head(10)
```
