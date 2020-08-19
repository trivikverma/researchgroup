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
    weight: 7

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---

1. [Lab 0: Tools](#Lab-0---tools) (Sep 2, 2020)
2. [Lab 1: Spatial and Urban Data](#Lab-2---spatial-and-urban-data) (Sep 7, 2020)
3. [Lab 2: Data Scraping and Grammar](#Lab-3---data-scraping-and-grammar) (Sep 9, 2020)
4. [Lab 3: Data Engineering and Transformations](#Lab-4---data-engineering-and-transformations) (Sep 14, 2020)
5. [Lab 4 EDA and Visualisation:](#Lab-5---eda-and-visualisation) (Sep 21, 2020)
6. [Lab 5: Geo-Visualisation](#Lab-6---geo-visualisation) (Sep 23, 2020)
7. [Lab 6: Networks and Spatial Weights](#Lab-7---networks-and-spatial-weights) (Sep 28, 2020)
8. [Lab 7: Exploratory Spatial Data Analysis](#Lab-8---exploratory-spatial-data-analysis) (Sep 30, 2020)
9. [Lab 8: Machine Learning for Everyone](#Lab-9---machine-learning-for-everyone) (Oct 5, 2020)

<br/>
<br/>


<br/>

***
<br/>

## Lab 0 - Tools


**IMPORTANT** This is a supplementary notebook that covers many basics of the tools we will use in the course, but does not explain anything directly related to Geographic Data Science.

Students are encouraged to read it once before getting started with the other notebooks and then keep it as a reference throughout the rest of the course.

---

**TIP**: Here you can find a step-by-step tutorial about how to start up the notebook, download files, and access them through the notebook:

> [[HTML](../content/labs/begin.html)]


### Notebook

- [ipynb](../labs/lab_00.ipynb)
- [html](../labs/lab_00.html)
- [pdf](../labs/lab_00.pdf)

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

## Lab 2 - Spatial and Urban Data

### Slides

- [html]()
- [pdf]()

### To do before class

* Watch the [TED talk](https://www.youtube.com/watch?v=CijsvAGU6-c) by Carlo Rati about MIT's SENSEable City Lab projects: excellent set of examples
* Read the [New York Times piece](https://www.nytimes.com/interactive/2018/10/12/us/map-of-every-building-in-the-united-states.html) on US buildings map
* Explore the [GHSL](https://ghsl.jrc.ec.europa.eu/index.php) Dataset, by the European Commission

### Related readings

* The part of the Lab on new sources of data relies on (Arribas-Bel, 2014) and (Lazer & Radford, 2017).
* (Goodchild, 2007): a classic on the rise of volunteered geographic information.
* (Kitchin, 2014): recent book on the data revolution from a Social Science/Human geography perspective.

### References

1. Arribas-Bel, D. (2014). Accidental, open and everywhere: Emerging data sources for the understanding of cities . Applied Geography , 49, 45–53.
2. Lazer, D., & Radford, J. (2017). Data ex Machina: Introduction to Big Data. Annual Review of Sociology, (0).
3. Goodchild, M. F. (2007). Citizens as sensors: the world of volunteered geography. GeoJournal, 69(4), 211–221.
4. Kitchin, R. (2014). The data revolution: Big data, open data, data infrastructures and their consequences. Sage.

<br/>

***
<br/>

## Lab 3 - Data Scraping and Grammar

### Slides

- [html]()
- [pdf]()

### To do before class

* Read a very influential pro-big data/data science article, [The End of Theory](https://www.wired.com/2008/06/pb-theory/) by Chris Anderson, the editor in chief of _Wired_.
* Read [A reflexive call of caution](https://science.sciencemag.org/content/343/6176/1203) on Big Data Analytics by David Lazer _et al._

### Related readings

* A cheatsheet (such a misnomer -- nobody is cheating and it is a helpful and beautiful resource) on [Data Wrangling with Pandas](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) that you may want to stick to your wall or put as your screensaver to save time on finding useful and operational codes.

<br/>

***
<br/>

## Lab 4 - Data Engineering and Transformations

### Slides

- [html]()
- [pdf]()

### To do before class

* Read a short blog on [Why, How and When to Scale your features](https://medium.com/greyatom/why-how-and-when-to-scale-your-features-4b30ab09db5e)

### Related readings

The contents of this Lab are loosely based on, and explored into further detail, in the following two references :

* Section 9.3.1 of [The Hundred-Page Machine Learning Book](https://leanpub.com/theMLbook) by Andriy Burkov.
* A more academically suited blog on [Feature Scaling](https://sebastianraschka.com/Articles/2014_about_feature_scaling.html)

<br/>

***
<br/>

## Lab 5 - EDA and Visualisation

This Lab is partly inspired by (Tufte, 1983).

### Slides

- [html]()
- [pdf]()

### To do before class

* Watch this short [video](https://www.youtube.com/watch?v=j8g4_ee27Tk) on data visualisation by Nathan Yau
* [Think about the grammar of graphics when improving your graphs](https://medium.com/tdebeus/think-about-the-grammar-of-graphics-when-improving-your-graphs-18e3744d8d18) - at _Colourful Facts_ – a Medium blog by Thomas de Beus (Ignore the reference to the **R** programming language as this course is based on **Python** (no offense intended to any community).)

### Related readings

* Berinato, S. Visualizations That Really Work, Harvard Business Review, Jun 2016
* Wainer, H. How to Display Data Badly. The American Statistician 1984; 38: 137-1470
* Alberto Cairo's weblog called [The Functional Art](http://www.thefunctionalart.com/) about information design and visualisation is a great resource for improving your visualisations.
* (Yau, 2011)’s book ["Visualize this"](http://flowingdata.com/visualize-this/)
  is a good general introduction to visualisation.
* Check out [From Data to Vis](https://www.data-to-viz.com/) chart selector for selecting the right charts

### References

1. Tufte, E. R. (1983). The visual display of quantitative information. Graphics press Cheshire, CT.
2. Yau, N. (2011). Visualize this: the FlowingData guide to design, visualization, and statistics. John Wiley & Sons.

<br/>

***
<br/>

## Lab 6 - Geo-Visualisation

This Lab is partly inspired by (Rey, 2015).

### Slides

- [html]()
- [pdf]()

### To do before class

* Watch this Lab on  "Statistical maps" by Luc Anselin ([link](https://www.youtube.com/watch?v=6-weK5J6xRI) to 25min video).
* Read the Conversation [piece](http://theconversation.com/how-zip-codes-nearly-masked-the-lead-problem-in-flint-65626) on the Flint case, where the MAUP played a key role.
* Spend the rest of the prep hour browsing through Nathan Yau's excellet blog, [Flowing Data](http://flowingdata.com/).

### Related readings

* (Brewer, 2015)’s [Designing Better Maps](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=293&moduleID=0) covers several aspects of building effective geovisualisations.
* [Choropleth chapter](https://geographicdata.science/book/notebooks/05_choropleth.html) from the GDS Book (in progress).
* Color palettes are important for maps. Find some in [ColorBrewer](http://colorbrewer2.org/).

### References

1. Rey, S. (2015). Geovisualization. In GPH471: Geographic Information Analysis. Lab slides from course taught at Arizona State University.
2. Brewer, C. (2015). Designing better Maps: A Guide for GIS users. ESRI press.

<br/>

***
<br/>

## Lab 7 - Networks and Spatial Weights

### Slides

- [html]()
- [pdf]()

### To do before class

* Read Eli Knaap's blog on [Measuring Urban Segregation with Spatial Computation](https://knaaptime.com/posts/segregation_dynamics/)
* Watch this Lab on  "Spatial Weights" by Luc Anselin ([link](https://www.youtube.com/watch?v=ydFmI6ZGLQ8) to 34min video). Keep in mind the motivation in this case is focused on spatial regression.
* Lab on "Special lag" by Luc Anselin ([link](https://www.youtube.com/watch?v=MQACCcfTpXc) to video, you can ignore the last five minutes as they are a bit more advanced).

### Related readings

* Check out Geoff Boeing's computational notebook showcasing the use of **OSMNX**- a python library for processing street networks as network objects- with a case of [Urban Street Network Analysis](https://escholarship.org/uc/item/6z9802kf.)
* For an advanced and in-detail treatment, (Anselin & Rey, 2014) is an excellent reference.

### References

1. Anselin, L., & Rey, S. J. (2014). Modern Spatial Econometrics in Practice: A Guide to GeoDa, GeoDaSpace and PySAL. Chicago, IL: GeoDa Press LLC.

<br/>

***
<br/>

## Lab 8 - Exploratory Spatial Data Analysis

### Slides

- [html]()
- [pdf]()

### To do before class

* Watch this Lab on "Spatial Autocorrelation (Background)" by Luc Anselin. [[Part I](https://www.youtube.com/watch?v=EotbDebRnFg)][[Part II](https://www.youtube.com/watch?v=69CnasXK2pM)]

### Related readings

* (Anselin, 1996) reviews the use of the Moran plot as an ESDA tool ([pdf](http://dces.wisc.edu/wp-content/uploads/sites/30/2013/08/W4_Anselin1996.pdf)).
* (Symanzik, 2014) introduces the main concepts behind ESDA.
* (Haining, 2014) is a good historical perspective of the origins and motivations behind most of global and local measures of spatial autocorrelation.

### References

1. Anselin, L. (1996). The Moran scatterplot as an ESDA tool to assess local instability in spatial association. Spatial Analytical Perspectives on GIS, 111, 111–125.
2. Symanzik, J. (2014). Exploratory Spatial Data Analysis. In Handbook of Regional Science (pp. 1295–1310). Springer.
3. Haining, R. (2014). Spatial Data and Statistical Methods: A Chronological Overview. In Handbook of Regional Science (pp. 1277–1294). Springer.
