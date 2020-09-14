---
title: Discussions
linktitle: Discussions
toc: true
type: docs
date: "2019-05-05T00:00:00Z"
draft: false
menu:
  epa1316-2020:
    name: Discussions
    weight: 60

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---

1. [Discussion 1: Big Data and Big Cities](#week-1---big-urban-data) (Sep 4, 2020)
2. [Discussion 2: Urban Data Sensing and Collection](#week-2---urban-data-sensing-and-collection) (Sep 11, 2020)
3. [Discussion 3: Measuring the Urban Condition](#week-3---measuring-the-urban-condition) (Sep 18, 2020)
4. [Discussion 4: Exploratory Spatial Interaction](#week-4---exploratory-spatial-interaction) (Sep 25, 2020)
5. [Discussion 5: Spatial Network Analysis](#week-5---spatial-network-analysis) (Oct 2, 2020)
6. [Discussion 6: Large-scale Urban Laws](#week-6---large-scale-urban-laws)(Oct 9, 2020)
7. [Discussion 7: Clustering the Urban Form](#week-7---clustering-the-urban-form) (Oct 16, 2020)
8. [Discussion 8: Ethics of Smart Cities](#week-8---ethics-of-smart-cities) (Oct 23, 2020)

<br/>

***
<br/>

## Guidelines for Reading

The objective of these reading discussions is,
- to explore how articles are written
- how data analysis is conducted and reported
- how to critically analyse literature
- learn to frame your own arguments using evidence
- practice your analytical skills for the final project

Your final project will benefit from these discussions. You can skip complex models and math equations introduced in these discussion papers but the bigger picture of why some models are preferred over other, or how to report data limitations and shortcomings of your work is important for the final assessment of this course. If you skip readings and discussions, you will fall behind in project work which amounts to 60% of your grade.

A short guide for reading these papers is mentioned below,

- Think about why your instructor assigned this reading. What subject will this article prepare you to discuss? How does this article fit into the main questions or topics of the course?
- Use the discussion questions as reading guides for the paper. (They will be posted a week before)
- Before you read in detail, skim the paper all the way through. Identify the organization of the document and the central ideas or arguments. The abstract, introduction, section headings and conclusion can provide information about the purpose and main point(s) about the paper.
- Using your first impression of the paper and the reading guides, you should read the main text purposefully, and decide where to place more attention. If you don't know critical terms and concepts, look them up in a dictionary, textbook, on the Internet or post on the appropriate discussion forum on Brightspace.
- If a complex model is explained, how would you simplify it or address the complexity differently? You may also choose to ignore the inner workings if it doesn't pertain to the course material and try to identify the use and application of that complex model.
- Did the reading clarify answers to the main point(s) of the article and raise other questions?
- The authors may not draw all possible conclusions of their analysis or provide all arguments to support it. You must be a critical reader! An author's view may not be in line with your own. Always keep in mind that reading academic writing means you're participating in a conversation. What do you learn from it if/how the reading sparked your thoughts is what you should reflect on.
- After reading the paper, try to summarize it in one paragraph. It should be your summary and not the abstract. Always use five questions as your guiding hand to write summaries. What do we know about the subject/problem? What is it that we do not know? How are we going to address it? What do we find with our method? Why is it relevant for research and policy?
- Besides, challenge the parts of the article which do not present a persuasive argument. What are, in your opinion, the strong points of the paper? If you were supposed to be a co-author, how would you make it a better article? If you were allowed to ask a question from the authors, what would you ask?


<br/>

***
<br/>

## Week 1 - Big Urban Data

Big Data and Big Cities: The Promises and Limitations of Improved Measures of Urban Life
<br/>
[[pdf](../discussions/week1.pdf)][[link](https://onlinelibrary.wiley.com/doi/abs/10.1111/ecin.12364)]

_The following questions do not necessarily pursue the order of the paper_

1. What is big data? What are the sources of big data in the cities? What is big data analytics?
2. How did the scholars use to address their research questions on urban science? What are the shortcomings of those approaches?
3. What kinds of analyses are facilitated by big data analytics?
4. How can crowdsourcing using digital apps and our digital traces (like mobile, OV-chipkaart, Google maps, Airbnb, etc.) help policymakers provide equitable distribution of resources (p135)?
5. What are some of the differences between old and new data sources? Should we use a combination of big data and conventional data sources in urban data science (page 124 and p133)?
6. How could we calculate the population of a city during the day and night? What kinds of data sources do you recommend? How should we use them?
7. How could big data analytics help to manage racial conflicts in the cities?

<br/>

***
<br/>

## Week 2 - Urban Data Sensing and Collection

(So) Big Data and the transformation of the city
<br/>
[[pdf](../discussions/week2.pdf)][[link](https://link.springer.com/article/10.1007/s41060-020-00207-3)]

1. What are the four main urban applications for which different algorithmic tools are discussed? What are the advantages and limitations associated with these algorithms? The paper classifies the algorithms into two main approaches: descriptive and predictive. What are the challenges of urban data science that each approach seeks to address?
2. What is the goal of Visual Analytics? What are the two main types of visual analytics that the paper covers? Identify the limitations of each approach. Can you think of more interesting use-cases for the datasets other than those discussed in the paper?
3. What is the text-cloud technique and what is its importance in urban data science? [In the paper, it is mentioned and used in multiple sections: visual analytics (of both textual content and images), GeoTopics modelling framework, algorithms etc]
4. What are the different data science techniques that this paper identifies to address three important challenges of urban data science? Identify at least 3 or 4 methods that may be familiar to you. At what part in the data science workflow are these techniques applied? Pick one case-study for an example.
5. What do you understand about the concept of “urban metabolism” discussed in the paper (towards the end of Section 4) and how does it influence sustainable development of cities?
6. How do Big Data and Smart Urban Metabolism overcome the limitations of urban metabolism and enhance sustainable development of cities?
7. What are some approaches suggested in the paper to tackle privacy issues that arise due to widespread availability of mobility data? What are some ways (in your opinion) to ensure a good balance between using data for social good and addressing privacy concerns?

<br/>

***
<br/>

## Week 3 - Measuring the Urban Condition

Road network vulnerability analysis: Conceptualization,implementation and application
<br/>
[pdf[^1]][[link - sign in with your TUD credentials to get access](https://www.sciencedirect.com/science/article/pii/S0198971514000192)]

[^1]: I cannot provide you with a PDF because of the absurd billion-dollar academic publishing industry

1. What is the goal of a network vulnerability analysis? When and why should policy makers use it?
2. How do the authors define vulnerability? What is the main difference between the two perspectives on vulnerability?
3. What is the difference between importance and criticality of a network element? When is a network link important?
4. What assumptions are made for computational reasons? And what are the implications of these assumptions on vulnerability studies?
5. Explain how the authors compute the travel time impact of a disruption (section 3.2). Would you compute it differently and why?
6. What data aggregation problem is mentioned in the application section of the paper (section 4.1)? Can you think of other network data aggregation consequences?
7. What are the main findings of the Swedish case study? What options are there to reduce vulnerability of a network? Reflect upon the concepts of redundancy, sparsity, density, hubs and how they influence expected user exposure.
8. What aspects are clearly (or not) understandable from Fig 4-6? What would you change or add to the visualization of network vulnerability?
9. Read the excerpt below and reflect on other examples of interdependent network failures. How would you expand the vulnerability analysis in those cases?

```markdown
A fundamental property of interdependent networks is that failure of nodes in one
network may lead to failure of dependent nodes in other networks. A dramatic real
world example of a cascade of failures (‘concurrent malfunction’) is the electrical
blackout that affected much of Italy on 28 September 2003: the shutdown of power
stations directly led to the failure of nodes in the Internet communication network,
which in turn caused further breakdown of power stations. (Extracted from article:
‘Catastrophic cascade of failures in interdependent networks’, Buldyrev, Sergey V.
and Parshani, Roni and Paul, Gerald and Stanley, H. Eugene and Havlin, Shlomo).
````

<br/>

***
<br/>

## Week 4 - Exploratory Spatial Interaction

Quantifying long-term evolution of intra-urban spatial interactions
<br/>
[[pdf](../discussions/week4.pdf)][[link](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2014.1089)]

<br/>

***
<br/>

## Week 5 - Spatial Network Analysis

Toward cities without slums: Topology and the spatial evolution of neighborhoods
<br/>
[[pdf](../discussions/week5.pdf)][[link](https://advances.sciencemag.org/content/4/8/eaar4644)][[post](https://miurban.uchicago.edu/2019/11/14/millionneighborhoodsmap/)][[tool](https://millionneighborhoods.org/#2/8.84/17.54)]

<br/>

***
<br/>

## Week 6 - Large-scale Urban Laws

Urban Scaling and Its Deviations: Revealing the Structure of Wealth, Innovation and Crime across Cities

[[pdf](../discussions/week6.pdf)][[link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0013541)]

<br/>

***
<br/>

## Week 7 - Clustering the Urban Form

Urban DNA and Sustainable Cities: A Multi-City Comparison

[[pdf](../discussions/week7.pdf)][[link](https://www.frontiersin.org/articles/10.3389/fenvs.2019.00004/full)]

<br/>

***
<br/>

## Week 8 - Ethics of Smart Cities

The ethics of smart cities and urban science

[[pdf](../discussions/week8.pdf)][[link](https://royalsocietypublishing.org/doi/full/10.1098/rsta.2016.0115)]
