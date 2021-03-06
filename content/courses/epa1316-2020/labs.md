---
title: Labs
linktitle: Labs
toc: true
type: docs
date: "2019-05-05T00:00:00Z"
draft: false
menu:
  epa1316-2020:
    name: Labs
    weight: 80

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---

1. [Lab 1: Tools](#lab-1---tools) (Sep 2, 2020)
2. [Lab 2: Tidy Data](#lab-2---tidy-data) (Sep 9, 2020)
3. [Lab 3: Data Engineering](#lab-3---data-engineering) (Sep 17[^1], 2020)
4. [Lab 4: Geo-Visualisation](#lab-4---geo-visualisation) (Sep 23, 2020)
5. [Lab 5: Networks and Spatial Weights](#lab-5---networks-and-spatial-weights) (Sep 30, 2020)
6. [Lab 6: Linear Regression](#lab-6---linear-regression) (Oct 7, 2020)
7. [Lab 7: Clustering](#lab-7---clustering) (Oct 14, 2020)
8. [Lab 8: Points](#lab-8---points) (Oct 21, 2020)

[^1]: On Sep 16th 2020, Wednesday, there is no lecture. I think that is because you have an EPA Programme session.

Note: The labs will be updated by at least the previous Friday for every week before it begins.

<br/>

***
<br/>

## Lab 1 - Tools

**IMPORTANT** This is a supplementary notebook that covers many basics of the tools we will use in the course but does not explain anything directly related to Urban Data Science.

Students are encouraged to read it once before getting started with the other notebooks and then keep it as a reference throughout the rest of the course. There are some basic Python operations in there that act as a refresher, practice or learning material.

### Notebook
- {{% staticref "epa1316-2020/labs/lab-01/lab-01.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-01/lab-01.html" "newtab" %}}lab-html{{% /staticref %}}

### Additional materials

If you want to explore further by yourself the contents presented in this tutorial, the following pointers are good places to start:

* [**Video**] ["Python as Super Glue for the Modern Scientific Workflow"](https://www.youtube.com/watch?v=mLuIB8aW2KA), keynote speech by Prof. Joshua Bloom from UC Berkley about how Python is used in Astronomy research.
* Gallery of [interesting notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks): a wealth of examples of Jupyter (formerly called IPython) notebooks.
* (Downey, 2012): very good general introduction to Python as a programming language and to the algorithmic way of thinking. The [book](http://www.greenteapress.com/thinkpython/thinkpython.html) is freely available in [HTML](http://www.greenteapress.com/thinkpython/html/index.html) and [PDF](http://www.greenteapress.com/thinkpython/thinkpython.pdf).

### References

1. Downey, A. (2012). Think Python - How to Think Like a Computer Scientist. Green Tea Press.

<br/>

***
<br/>

## Lab 2 - Tidy Data

### Notebook

- {{% staticref "epa1316-2020/labs/lab-02/lab-02.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-02/lab-02.html" "newtab" %}}lab-html{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-02/lab-02-extra.html" "newtab" %}}lab-extra-html{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-02/lab-02-advanced.html" "newtab" %}}lab-advanced-html{{% /staticref %}}

### Data

This session uses the **"Census socio-demographics"** dataset of Liverpool, United Kingdom in two parts. The dataset for this lab is provided in the zipped lab files above.

1. Table of LSOA areas in Liverpool with population counts by World region. The table is derived from the CDRC Census data pack.
2. Collection of socio-demographic characteristics from the 2011 Census for the city of Liverpool.

### Additional materials

* A good extension of this session is (Wickham, 2014). The paper is published under an Open Access license, so it is freely available on the journal's site, but the author has also made available a public [repository](https://github.com/hadley/tidy-data) with the data and code used in the paper. Keep in mind the paper, and the code that comes with it is based on R, not on Python.
* **[Visualization]** Python library `seaborn` [tutorial](http://stanford.edu/~mwaskom/software/seaborn/tutorial.html).
* **[Recommended]** (McKinney, 2012): An excellent introduction to Python for data analysis, with plenty of examples and code snippets (Publisher's page [link](http://shop.oreilly.com/product/0636920023784.do)).
* [NY Times article](http://www.nytimes.com/2014/08/18/technology/for-big-data-scientists-hurdle-to-insights-is-janitor-work.html?_r=0) about the importance of cleaning data.

### References

1. Wickham, H. (2014). Tidy Data. Journal of Statistical Software, 59(10).
2. McKinney, W. (2012). Python for data analysis: Data wrangling with Pandas, NumPy, and IPython. O’Reilly Media, Inc.

<br/>

***
<br/>

## Lab 3 - Data Engineering

### Notebook

- {{% staticref "epa1316-2020/labs/lab-03/lab-03.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-03/lab-03.html" "newtab" %}}lab-html{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-03/lab-03-advanced.html" "newtab" %}}lab-advanced-html{{% /staticref %}}

### Data

This session uses two datasets which are provided in the zipped lab files above.

1. A dataset about wines from different countries, download from *Kaggle*.
2. A dataset scraped and collected from **Goodreads**.

<br/>

***
<br/>

## Lab 4 - Geo-Visualisation

Lab 4 homework exercises are embedded within the lab files itself. You have to complete the exercises as you go along understanding the rest of the code. There are two files for this lab, ``geovis`` and ``eda``. Submit one or both together as **one** zip file on _Peer_ when you are done. Since this geocomputational lab is not as straightforward as other python code, a **solution set** will be provided for questions indicated in the lab after submission ends.

### Notebook

- {{% staticref "epa1316-2020/labs/lab-04/lab-04.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-04/lab-04-geovis.html" "newtab" %}}lab-geovis-html{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-04/lab-04-EDA.html" "newtab" %}}lab-eda-html{{% /staticref %}}

### Solutions

- {{% staticref "epa1316-2020/labs/lab-04/solutions.zip" "newtab" %}}lab-solutions-zip{{% /staticref %}}

### Data

This session uses multiple datasets which are provided in the zipped lab files above.

1. A **"Census socio-demographics"** dataset as well as the Ordnance Survey **(OS) Geodata Pack**.
2. An **"Index of Multiple Deprivation""** dataset as well as the Ordnance Survey **(OS) Geodata Pack**.
Scores, ranks, and components of the 2015 Index of Multiple Deprivation (IMD).
**Source**: [CDRC](http://cdrc.ac.uk/)'s English Indices of Deprivation 2015 Geodata Pack for the city of Liverpool (UK).
3. Additionally, you will need the raster file for the basemap of Liverpool. This has been assembled by [Dani Arribas-Bel](http://darribas.org) from the [OS VectorMap District (Backdrop Raster)](https://www.ordnancesurvey.co.uk/business-and-government/products/vectormap-district.html), and it is licensed as OpenData.
4. Simple datasets on ``heart diseases``, ``titanic`` and a ``mystery`` you can find out for yourself.

### Additional materials

* A good introduction to the `geopandas` project is provided by Kelsey Jordahl, the project's founder in this [set of slides](http://kjordahl.github.io/SciPy-Tutorial-2015/#1) from a 2015 talk and the companion [repository](https://github.com/kjordahl/SciPy-Tutorial-2015).
* An additional great resource is this 4h. [workshop](https://github.com/carsonfarmer/python_geospatial) by Carson Farmer.

<br/>

***
<br/>

## Lab 5 - Networks and Spatial Weights

### Notebook

- {{% staticref "epa1316-2020/labs/lab-05/lab-05.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-05/lab-05.html" "newtab" %}}lab-geovis-html{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-05/lab-05-advanced.html" "newtab" %}}lab-eda-html{{% /staticref %}}

### Data

This session uses multiple datasets which are all provided in the zipped lab files above or separately as a _Brexit_ zip file.

1. An **"Index of Multiple Deprivation""** dataset used in previous labs.
2. A **Brexit** dataset.

This is the dataset of the results of the 2016 referendum vote to leave the EU, at the local authority level. All the necessary data have been assembled for convenience in a single file that contains geographic information about each local authority in England, Wales and Scotland, as well as the vote attributes. The file is in the modern geospatial format [GeoPackage](http://www.geopackage.org/), which presents several advantages over the more traditional shapefile (chief among them, the need of a single file instead of several). The file is provided below,

- {{% staticref "epa1316-2020/labs/lab-05/brexit.zip" "newtab" %}}brexit-data{{% /staticref %}}

Unzip and add this file to the data folder as well.

The source data used to compile the file linked above include:

- Electoral Commission data on the EU referendum results ([`url`](https://www.electoralcommission.org.uk/find-information-by-subject/elections-and-referendums/past-elections-and-referendums/eu-referendum/electorate-and-count-information))
- Local Authority District boundaries ([`url`](https://data.gov.uk/dataset/83f065f7-3b55-4871-97c8-21579adbee1c/local-authority-districts-december-2015-full-extent-boundaries-in-great-britain))

### Required before the practical

Watch the section on spatial weights of the SciPy'16 tutorial on Geographic Data Science with PySAL.

> [[YouTube](https://youtu.be/TY4QWnnd4jY?t=1h2m55s) - Min 1:02:55 to 1:25:40]

Watch the section on ESDA of the SciPy'16 tutorial on Geographic Data Science with PySAL.

> [[YouTube](https://youtu.be/TY4QWnnd4jY?t=1h25m40s) - Min 1:25:40 to 1:49:20] [[Online materials](http://darribas.org/gds_scipy16/ipynb_md/04_esda.html)]

### Additional materials

* The ["User Guides"](https://pysal.org/getting_started) in `PySAL`'s documentation are an excellent resource to better get to know the library.

<br/>

***
<br/>

## Lab 6 - Linear Regression

Since this lab is not as straightforward as other python code, a **solution set** will be provided for questions indicated in the homework after submission ends. Lab solutions are already provided but it is better if you try yourself and get feedback, then look at the solutions.

### Notebook

- {{% staticref "epa1316-2020/labs/lab-06/lab-06.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-06/lab-06.html" "newtab" %}}lab-html{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-06/lab-06-advanced.html" "newtab" %}}lab-advanced-html{{% /staticref %}}

### Solutions

- {{% staticref "epa1316-2020/labs/lab-06/solutions.zip" "newtab" %}}lab-solutions-zip{{% /staticref %}}

### Data

This session uses multiple data files.

1. A dataset downloaded from Kaggle on stats about the premiere league.
2. A Boston housing dataset and its training set companion.
3. An IMDB cast dataset.
4. A car dataset.
5. A cab dataset.

These sets are not that relevant to the worlds problems but simple to work with on small regression practice sets.

<br/>

***
<br/>

## Lab 7 - Clustering

### Notebook

- {{% staticref "epa1316-2020/labs/lab-07/lab-07.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-07/lab-07.html" "newtab" %}}lab-html{{% /staticref %}}

### Data

This session uses the **"AirBnb listing for Inner London - MSOA level"** dataset.

This dataset contains information for [AirBnb](https://www.airbnb.com) properties for the area of Inner London aggregated at the MSOA level. It has been prepared by Dani Arribas-Bel using as the original source the full listing of AirBnb locations for London provided by [Inside AirBnb](https://insideairbnb.com/). Same as the source, the dataset is released under a [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) License.

For every polygon, the following variables are provided:

* `id`: MSOA unique identifier.
* `accommodates`: average property capacity in the MSOA.
* `bathrooms`: average number of bathrooms in the properties within the MSOA.
* `bedrooms`: average number of bedrooms in the properties within the MSOA.
* `beds`: average number of beds in the properties within the MSOA.
* `number_of_reviews`: average number of reviews received by the properties within the MSOA.
* `reviews_per_month`: average number of reviews per month received by the properties within the MSOA.
* `review_scores_ratings`: average rating score received by the properties within the MSOA.
* `review_scores_accuracy`: average accuracy score received by the properties within the MSOA.
* `review_scores_cleanliness`: average cleanliness score received by the properties within the MSOA.
* `review_scores_checkin`: average checkin score received by the properties within the MSOA.
* `review_scores_communication`: average communication score received by the properties within the MSOA.
* `review_scores_location`: average location score received by the properties within the MSOA.
* `review_scores_value`: average value score received by the properties within the MSOA.
* `property_count`: total number of AirBnb properties listed withing the MSOA.

The lab also uses an additional file that contains the boundary lines of the London boroughs provided in the data fodler as well.

### Required before the practical

Watch the section on spatial clustering of the SciPy'16 tutorial on Geographic Data Science with PySAL.

> [[YouTube](https://youtu.be/TY4QWnnd4jY?t=2h30m) - Min 2:30:00 to 3:02:00]

### Additional materials

* Although a bit more advanced, the documentation for [`scikit-learn`](http://scikit-learn.org), a world-class Python library for machine learning, is excellent and includes many examples that cover the entire functionality set of the library.

<br/>

***
<br/>

## Lab 8 - Points

You do not have to submit Lab 8 for peer feedback. It is for your own practice.

### Notebook

- {{% staticref "epa1316-2020/labs/lab-08/lab-08.zip" "newtab" %}}lab-zip{{% /staticref %}}
- {{% staticref "epa1316-2020/labs/lab-08/lab-08.html" "newtab" %}}lab-html{{% /staticref %}}

### Data

This lab uses a sample of geo-referenced locations of photographs taken in Tokyo.

### Required before the practical

Watch the section on points of the SciPy'16 tutorial on Geographic Data Science with PySAL.

> [[YouTube](https://youtu.be/TY4QWnnd4jY?t=1h50m) - Min 1:50:00 to 2:30:00]

### Additional materials

* A very good resource for kernel density estimation in Python is provided in [this blog post](https://jakevdp.github.io/blog/2013/12/01/kernel-density-estimation/) by Jake Vanderplas.
* The R package [`spatstat`](http://spatstat.github.io/) provides extensive functionality to statistically describe and model point patterns. Note that this is in R, not Python.
