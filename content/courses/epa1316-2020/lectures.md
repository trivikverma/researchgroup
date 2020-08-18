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
3. [Lecture 3: Data Scraping and Grammar](#lecture-3---data-scraping-and-grammar) (Sep 9, 2020)
4. [Lecture 4: Data Engineering and Transformations](#lecture-4---data-engineering-and-transformations) (Sep 14, 2020)
5. [Lecture 5 EDA and Visualisation:](#lecture-5---eda-and-visualisation) (Sep 21, 2020)
6. [Lecture 6: Geo-Visualisation](#lecture-6---geo-visualisation) (Sep 23, 2020)
7. [Lecture 7: Networks and Spatial Weights](#lecture-7---networks-and-spatial-weights) (Sep 28, 2020)
8. [Lecture 8: Exploratory Spatial Data Analysis](#lecture-8---exploratory-spatial-data-analysis) (Sep 30, 2020)
9. [Lecture 9: Machine Learning for Everyone](#lecture-9---machine-learning-for-everyone) (Oct 5, 2020)
10. [Lecture 10: Anatomy of a Learning Algorithm](#lecture-10---anatomy-of-a-learning-algorithm) (Oct 7, 2020)
11. [Lecture 11: Clustering](#lecture-11---clustering) (Oct 12, 2020)
12. [Lecture 12: Dimensionality Reduction](#lecture-12---dimensionality-reduction) (Oct 14, 2020)
13. [Lecture 13: Spatial Density Estimation](#lecture-13---spatial-density-estimation) (Oct 19, 2020)
14. [Lecture 14: Responsible Data Science](#lecture-14---responsible-data-science) (Oct 21, 2020)

<br/>
<br/>

{{% alert note %}}
Before starting this course, watch [this video](https://www.youtube.com/watch?v=8jqEj8XUPlk&t=80s) by Khalid Kadir about a reflection on poverty (an example of a social problem), expertise and equity. This representation is an example of how experts form boxes around their craft. As a data scientist or a future AI expert, it is our responsibility to step out of those boxes and engage with communities to strive for just outcomes.
{{% /alert %}}

{{< youtube 8jqEj8XUPlk >}}

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

* Read [What New Yorkers are complaining about](https://www.wired.com/2010/11/ff_311_new_york/) and reflect on [if the cost of running such data systems worth the price of knowing?](https://www.governing.com/topics/urban/gov-311-systems-cost.html)

### Related readings

The contents of this lecture are loosely based on, and explored into further detail, in the following four references :

* **[Recommended]** "Chapter 1: Introduction" (Schutt & O’Neil, 2013). Free sampler of the book containing the chapter available online ([html](http://shop.oreilly.com/product/0636920028529.do), [pdf](http://cdn.oreillystatic.com/oreilly/booksamplers/9781449358655_sampler.pdf)).
* Excellent overview of Data Science (Donoho, 2017).
* A Geographic take on Data Science, proposing a new field (Singleton & Arribas-Bel, 2019).
* [A critical approach to Data Science for Cities](https://hdsr.mitpress.mit.edu/pub/1um18ajd/release/1)

### References

1. Schutt, R., & O’Neil, C. (2013). Doing data science: Straight talk from the frontline. “ O’Reilly Media, Inc.”
2. Donoho, D. (2017). 50 years of data science. Journal of Computational and Graphical Statistics, 26(4), 745–766.
3. Singleton, A., & Arribas-Bel, D. (2019). Geographic Data Science. Geographical Analysis.

<br/>

***
<br/>

## Lecture 2 - Spatial and Urban Data

### Slides

- [html]()
- [pdf]()

### To do before class

* Watch the [TED talk](https://www.youtube.com/watch?v=CijsvAGU6-c) by Carlo Rati about MIT's SENSEable City Lab projects: excellent set of examples
* Read the [New York Times piece](https://www.nytimes.com/interactive/2018/10/12/us/map-of-every-building-in-the-united-states.html) on US buildings map
* Explore the [GHSL](https://ghsl.jrc.ec.europa.eu/index.php) Dataset, by the European Commission

### Related readings

* The part of the lecture on new sources of data relies on (Arribas-Bel, 2014) and (Lazer & Radford, 2017).
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

## Lecture 3 - Data Scraping and Grammar

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

## Lecture 4 - Data Engineering and Transformations

### Slides

- [html]()
- [pdf]()

### To do before class

* Read a short blog on [Why, How and When to Scale your features](https://medium.com/greyatom/why-how-and-when-to-scale-your-features-4b30ab09db5e)

### Related readings

The contents of this lecture are loosely based on, and explored into further detail, in the following two references :

* Section 9.3.1 of [The Hundred-Page Machine Learning Book](https://leanpub.com/theMLbook) by Andriy Burkov.
* A more academically suited blog on [Feature Scaling](https://sebastianraschka.com/Articles/2014_about_feature_scaling.html)

<br/>

***
<br/>

## Lecture 5 - EDA and Visualisation

This lecture is partly inspired by (Tufte, 1983).

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

## Lecture 6 - Geo-Visualisation

This lecture is partly inspired by (Rey, 2015).

### Slides

- [html]()
- [pdf]()

### To do before class

* Watch this lecture on  "Statistical maps" by Luc Anselin ([link](https://www.youtube.com/watch?v=6-weK5J6xRI) to 25min video).
* Read the Conversation [piece](http://theconversation.com/how-zip-codes-nearly-masked-the-lead-problem-in-flint-65626) on the Flint case, where the MAUP played a key role.
* Spend the rest of the prep hour browsing through Nathan Yau's excellet blog, [Flowing Data](http://flowingdata.com/).

### Related readings

* (Brewer, 2015)’s [Designing Better Maps](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=293&moduleID=0) covers several aspects of building effective geovisualisations.
* [Choropleth chapter](https://geographicdata.science/book/notebooks/05_choropleth.html) from the GDS Book (in progress).
* Color palettes are important for maps. Find some in [ColorBrewer](http://colorbrewer2.org/).

### References

1. Rey, S. (2015). Geovisualization. In GPH471: Geographic Information Analysis. Lecture slides from course taught at Arizona State University.
2. Brewer, C. (2015). Designing better Maps: A Guide for GIS users. ESRI press.

<br/>

***
<br/>

## Lecture 7 - Networks and Spatial Weights

### Slides

- [html]()
- [pdf]()

### To do before class

* Read Eli Knaap's blog on [Measuring Urban Segregation with Spatial Computation](https://knaaptime.com/posts/segregation_dynamics/)
* Watch this lecture on  "Spatial Weights" by Luc Anselin ([link](https://www.youtube.com/watch?v=ydFmI6ZGLQ8) to 34min video). Keep in mind the motivation in this case is focused on spatial regression.
* Lecture on "Special lag" by Luc Anselin ([link](https://www.youtube.com/watch?v=MQACCcfTpXc) to video, you can ignore the last five minutes as they are a bit more advanced).

### Related readings

* Check out Geoff Boeing's computational notebook showcasing the use of **OSMNX**- a python library for processing street networks as network objects- with a case of [Urban Street Network Analysis](https://escholarship.org/uc/item/6z9802kf.)
* For an advanced and in-detail treatment, (Anselin & Rey, 2014) is an excellent reference.

### References

1. Anselin, L., & Rey, S. J. (2014). Modern Spatial Econometrics in Practice: A Guide to GeoDa, GeoDaSpace and PySAL. Chicago, IL: GeoDa Press LLC.

<br/>

***
<br/>

## Lecture 8 - Exploratory Spatial Data Analysis

### Slides

- [html]()
- [pdf]()

### To do before class

* Watch this lecture on "Spatial Autocorrelation (Background)" by Luc Anselin. [[Part I](https://www.youtube.com/watch?v=EotbDebRnFg)][[Part II](https://www.youtube.com/watch?v=69CnasXK2pM)]

### Related readings

* (Anselin, 1996) reviews the use of the Moran plot as an ESDA tool ([pdf](http://dces.wisc.edu/wp-content/uploads/sites/30/2013/08/W4_Anselin1996.pdf)).
* (Symanzik, 2014) introduces the main concepts behind ESDA.
* (Haining, 2014) is a good historical perspective of the origins and motivations behind most of global and local measures of spatial autocorrelation.

### References

1. Anselin, L. (1996). The Moran scatterplot as an ESDA tool to assess local instability in spatial association. Spatial Analytical Perspectives on GIS, 111, 111–125.
2. Symanzik, J. (2014). Exploratory Spatial Data Analysis. In Handbook of Regional Science (pp. 1295–1310). Springer.
3. Haining, R. (2014). Spatial Data and Statistical Methods: A Chronological Overview. In Handbook of Regional Science (pp. 1277–1294). Springer.

<br/>

***
<br/>

## Lecture 9 - Machine Learning for Everyone

Kindly buy [The Hundred-Page Machine Learning Book](https://leanpub.com/theMLbook) as _some_ chapters will be used in _some_ topics from this point onwards and it is generally an amazing book to have. If you cannot or do not want to spend $20.00 on the e-copy, email me and we will figure something out. The author has invested a lot in writing this book and it is an excellent resource on Machine Learning, even beyond this class.

### Slides

- [html]()
- [pdf]()

### To do before class

[A Visual Introduction to Machine Learning by r2d3](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/). It is a wonderful two-part series.

* **[Recommended]** [Part I: A Decision Tree](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

### Related readings

The contents of this lecture are loosely based on, and explored into further detail, in the following two references :

* Chapter 1 and section 3.1 of [The Hundred-Page Machine Learning Book](https://leanpub.com/theMLbook) by Andriy Burkov.
* [A Visual Introduction to Machine Learning by r2d3](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
* **[Extra and optional]** [Part II: Model Tuning and the Bias-Variance Tradeoff](http://www.r2d3.us/visual-intro-to-machine-learning-part-2/)

<br/>

***
<br/>

## Lecture 10 - Anatomy of a Learning Algorithm

### Slides

- [html]()
- [pdf]()

### To do before class

* Read [An accessible introduction to how machine learning is applied in urban design: a generative design tool](https://ui.kpf.com/smarter-city)
* Go through this amazing medium post about [A first step toward the future of neighborhood design](https://medium.com/sidewalk-talk/a-first-step-toward-the-future-of-neighborhood-design-a2777ad69550)

### Related readings

* [Explainable ML/AI: Why Are We Using Black Box Models in AI When We Don’t Need To?](https://hdsr.mitpress.mit.edu/pub/f9kuryi8/release/5)

<br/>

***
<br/>

## Lecture 11 - Clustering

### Slides

- [html]()
- [pdf]()

### To do before class

* Talk on "Geodemographics and the Internal Structure of Cities" by Prof. Alex Singleton ([link](https://www.youtube.com/watch?v=lslLujtqGlw) to 50min. video).

### Related readings

* Chapters 1 and 2 in (Webber & Burrows, 2018) provides a fascinating account of the origins of Geodemographic classifications.
* Chapter 7 in (Brunsdon & Singleton, 2015): *Geodemographic Analysis*, by Alexandros Alexiou and Alex Singleton.
* (Duque, Ramos, & Suriñach, 2007) is an excellent review of regionalization algorthims, but it is an advanced read.
* (Oke et al., 2019) provides a very nice urban framework using hierarchical clustering methods and diverse set of abundant data.

### References

1. Webber, R., & Burrows, R. (2018). The Predictive Postcode: The Geodemographic Classification of British Society. SAGE.
2. Brunsdon, C., & Singleton, A. (2015). Geocomputation: A Practical Primer. SAGE.
3. Duque, J. C., Ramos, R., & Suriñach, J. (2007). Supervised regionalization methods: A survey. International Regional Science Review, 30(3), 195–220.
4. Oke, J. B., Aboutaleb, Y. M., Akkinepally, A., Azevedo, C. L., Han, Y., Zegras, P. C., ... & Ben-Akiva, M. E. (2019). A novel global urban typology framework for sustainable mobility futures. Environmental Research Letters, 14(9), 095006.

<br/>

***
<br/>

## Lecture 12 - Dimensionality Reduction

### Slides

- [html]()
- [pdf]()

### To do before class

* Read through this excellent step-wise example of [Principal Component Analysis](https://gmaclenn.github.io/articles/airport-pca-analysis/) using airport delay data
* Read this excellent community-driven explanation of [PCA](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues) on stackexchange.

### Related readings

The contents of this lecture are loosely based on, and explored into further detail, in the following reference :

* Section 9.3.1 of [The Hundred-Page Machine Learning Book](https://leanpub.com/theMLbook) by Andriy Burkov.



<br/>

***
<br/>

## Lecture 13 - Spatial Density Estimation

### Slides

- [html]()
- [pdf]()

### To do before class

* Lecture on  "Point Pattern Analysis Basics" by Luc Anselin ([link](https://www.youtube.com/watch?v=Z2iT4JpqGZg&list=PLzREt6r1NenlmAiF3ds5_WGVAG1rTYSK-&index=1) to 45min video, and [link](https://www.youtube.com/watch?v=BN94XXT6Io4) to a more recent 6 min intro).

### Related readings

* This class was partially based on (Rey, 2015).
* The slides for this lecture were also inspired by Part 6 in (C. Brunsdon, 2015).

### References

1. Rey, S. (2015). Point Pattern Basics. In GPH471: Geographic Information Analysis. Lecture slides from course taught at Arizona State University.
2. C. Brunsdon, L. C. (2015). An Introduction to R for Spatial Analysis and Mapping. SAGE Publications Ltd.


<br/>

***
<br/>

## Lecture 14 - Responsible Data Science

### Slides

- [html]()
- [pdf]()

### To do before class

* Read [A city is not a computer](https://placesjournal.org/article/a-city-is-not-a-computer/?cn-reloaded=1), Shannon Mattern which carefully examines the limitations of computation in bettering human condition.
* Explore the [Gender Shades](http://gendershades.org/overview.html) project by Joy Buolamwini and Timnit Gebru that uncovers the priorities, preferences and prejudices of powerful organisations that develop automated systems.
* Read and critically examine a post by Sidewalk Labs: [An Update on Data Governance for Sidewalk Toronto](https://www.sidewalklabs.com/blog/an-update-on-data-governance-for-sidewalk-toronto/)

### Related readings

* Watch [The unfortunate history of racial bias in photography.](https://www.youtube.com/watch?v=d16LNHIEJzs).
* (El-Geneidy et al., 2016) describe the cost of equity in assessing transit accessibility and social disparity using total travel cost.

### References

1. El-Geneidy, A., Levinson, D., Diab, E., Boisjoly, G., Verbich, D., & Loong, C. (2016). The cost of equity: Assessing transit accessibility and social disparity using total travel cost. Transportation Research Part A: Policy and Practice, 91, 302-316.
