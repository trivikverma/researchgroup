---
title: Lectures
linktitle: Lectures
toc: true
type: docs
date: "2019-05-05T00:00:00Z"
draft: false
menu:
  epa1316-2020:
    name: Lectures
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---

1. [Lecture 1: Introduction to _Urban_ Data Science](#lecture-1---introduction-to-urban-data-science) (Sep 2, 2020)
2. [Lecture 2: Spatial and Urban Data](#lecture-2---spatial-and-urban-data) (Sep 7, 2020)
3. [Lecture 3 - Introduction to _Urban_ Data Science](#lecture-2) (Sep 9, 2020)

<br/>

***
<br/>

## Lecture 1 - Introduction to Urban Data Science

### Slides

- [html]()
- [pdf](../lectures/01-introduction.pdf)

### To do before class

As a way to wet your apetite about the content of the first class, I recommend you:

* Listen to [this interview](http://www.sciencefriday.com/segments/solving-lifes-everyday-problems-with-data/) with Hilary Mason, Max Shron, and Alex Pentland about the power of data.

* Watch [this video](https://www.youtube.com/watch?v=h1ImEQKSkUQ) by Mike Flowers, Chief Analytics Officer, at the City of New York about how data is used to influence policy decisions.

* and finally, watch [this video](https://www.youtube.com/watch?v=8jqEj8XUPlk&t=80s) by Khalid Kadir about a reflection on poverty (an example of a social problem), expertise and equity. This representation is an example of how experts form boxes around their craft. As a data scientist or a future AI expert, it is our responsibility to step out of those boxes and engage with communities to strive for just outcomes.

{{< youtube 8jqEj8XUPlk >}}

### Related readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]** "Chapter 1: Introduction" {% cite schutt2013doing %}. Free sampler of the book containing the chapter available online ([html](http://shop.oreilly.com/product/0636920028529.do), [pdf](http://cdn.oreillystatic.com/oreilly/booksamplers/9781449358655_sampler.pdf)).
* Excellent overview of Data Science {% cite donoho201750 %}.
* A Geographic take on Data Science, proposing a new field {% cite singleton2019geographic %}.

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 2 - Spatial and Urban Data

### Slides

- [html]()
- [pdf]()

### To do before class

* [TED talk](https://www.youtube.com/watch?v=CijsvAGU6-c) by Carlo Rati about MIT's SENSEable City Lab projects: excellent set of examples
* [New York Times piece](https://www.nytimes.com/interactive/2018/10/12/us/map-of-every-building-in-the-united-states.html) on US buildings map
* [GHSL](https://ghsl.jrc.ec.europa.eu/index.php) Dataset, by the European Comission

### Related readings

* The part of the lecture on new sources of data relies on {% cite ArribasBel201445 %}.
* {% cite goodchild2007citizens %}: a classic on the rise of volunteered geographic information.
* {% cite kitchin2014data %}: recent book on the data revolution from a Social Science/Human geography perspective.
* {% cite lazer2017data %}: recent paper contextualizing the rise of new forms of data and the potential they hold for Social Sciences.

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 3 - Data Grammar, Engineering and Scraping

### Slides

- [html]()
- [pdf]()

### To do before class

* Read a very influential pro-big data/data science article, [The End of Theory](https://www.wired.com/2008/06/pb-theory/) by Chris Anderson, the editor in chief of _Wired_.
* Read [A reflexive call of caution](https://science.sciencemag.org/content/343/6176/1203) on Big Data Analytics by David Lazer _et al._

### ### Related readings

* A cheatsheet (such a misnomer -- nobody is cheating and it is a helpful and beautiful resource) on [Data Wrangling with Pandas](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) that you may want to stick to your wall or put as your screensaver  to save time on finding useful and operational codes.

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 4 - EDA and Visualisation

### Slides

- [html]()
- [pdf]()

### To do before class

* (Short) [video](https://www.youtube.com/watch?v=j8g4_ee27Tk) on data visualisation by Nathan Yau
* [Think about the grammar of graphics when improving your graphs](https://medium.com/tdebeus/think-about-the-grammar-of-graphics-when-improving-your-graphs-18e3744d8d18) - at _Colourful Facts_ – a Medium blog by Thomas de Beus (Ignore the reference to the **R** programming language as this course is based on Python.)

### Related readings

* Berinato, S. Visualizations That Really Work, Harvard Business Review, Jun 2016
* Wainer, H. How to Display Data Badly. The American Statistician 1984; 38: 137-1470
* Alberto Cairo's weblog called [The Functional Art](http://www.thefunctionalart.com/) about information design and visualisation
  is a great resource for improving your visualisations.
* {% cite yau2011visualize %}'s book ["Visualize this"](http://flowingdata.com/visualize-this/)
  is a good general introduction to visualisation.
* Check out [From Data to Vis](https://www.data-to-viz.com/) chart selector for selecting the right charts

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 5 - Geo-Visualisation

### Slides

- [html]()
- [pdf]()

### To do before class

* Lecture on  "Statistical maps" by Luc Anselin ([link](https://www.youtube.com/watch?v=6-weK5J6xRI) to 25min video).
* The Conversation [piece](http://theconversation.com/how-zip-codes-nearly-masked-the-lead-problem-in-flint-65626) on the Flint case, where the MAUP played a key role.
* Spend the rest of the prep hour browsing through his excellet blog, [Flowing Data](http://flowingdata.com/).

### Related readings

* {% cite brewer2015designing %}'s [Designing Better Maps](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=293&moduleID=0) covers several aspects of building effective geovisualisations.
* [Choropleth chapter](https://geographicdata.science/book/notebooks/05_choropleth.html) from the GDS Book (in progress).
* Color palettes are important for maps. Find some in [ColorBrewer](http://colorbrewer2.org/).

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 6 - Networks and Spatial Weights

### Slides

- [html]()
- [pdf]()

### To do before class

* Read Eli Knaap's blog on [Measuring Urban Segregation with Spatial Computation](https://knaaptime.com/posts/segregation_dynamics/)
* Lecture on  "Spatial Weights" by Luc Anselin ([link](https://www.youtube.com/watch?v=ydFmI6ZGLQ8) to 34min video). Keep in mind the motivation in this case is focused on spatial regression.
* Lecture on "Special lag" by Luc Anselin ([link](https://www.youtube.com/watch?v=MQACCcfTpXc) to video, you can ignore the last five minutes as they are a bit more advanced).

### Related readings

* Check out Geoff Boeing's computational notebook showcasing the use of **OSMNX**- a python library for processing street networks as network objects- with a case of [Urban Street Network Analysis](https://escholarship.org/uc/item/6z9802kf.)
* For an advanced and in-detail treatment, {% cite anselin2014modern %} is an excellent reference.

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 7 - Exploratory Spatial Data Analysis

### Slides

- [html]()
- [pdf]()

### To do before class

* Lecture on "Spatial Autocorrelation (Background)" by Luc Anselin. [[Part I](https://www.youtube.com/watch?v=EotbDebRnFg)][[Part II](https://www.youtube.com/watch?v=69CnasXK2pM)]

### Related readings

* {% cite anselin1996moran %} reviews the use of the Moran plot as an ESDA tool ([pdf](http://dces.wisc.edu/wp-content/uploads/sites/30/2013/08/W4_Anselin1996.pdf)).
* {% cite symanzik2014exploratory %} introduces the main concepts behind ESDA.
* {% cite haining2014spatial %} is a good historical perspective of the origins and motivations behind most of global and local measures of spatial autocorrelation.

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 8 - Machine Learning for Everyone

### Slides

- [html]()
- [pdf]()

### To do before class



### Additional readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]**

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 9 - Anatomy of a Learning Algorithm

### Slides

- [html]()
- [pdf]()

### To do before class



### Additional readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]**

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 10 - Basic Practice

### Slides

- [html]()
- [pdf]()

### To do before class



### Additional readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]**

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 11 - Clustering

### Slides

- [html]()
- [pdf]()

### To do before class



### Additional readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]**

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 12 - Dimensionality Reduction

### Slides

- [html]()
- [pdf]()

### To do before class



### Additional readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]**

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 13 - Points + Density Estimation

### Slides

- [html]()
- [pdf]()

### To do before class



### Additional readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]**

### References

{% bibliography --cited %}

<br/>

***
<br/>

## Lecture 14 - Responsible Data Science

### Slides

- [html]()
- [pdf]()

### To do before class



### Additional readings

The contents of this lecture are loosely based on, and explored into further detail, in the following three references :

* **[Recommended]**

### References

{% bibliography --cited %}
