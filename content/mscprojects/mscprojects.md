+++
# Blank widget.
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 21  # Order that this section will appear.

title = "Available Master's Thesis Projects"
subtitle = "Academic Year 2020-21"

# Date format for experience
#   Refer to https://sourcethemes.cm/academic/docs/customization/#date-format
date_format = "Jan 2006"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

+++

-----

<br />

### 1. Analysing the socio-demographic and environmental impacts of on-demand transit across multiple cities.

Achieving inclusion and fairness in policy interventions within cities has become a central objective for urban planners around the world. Modern cities have challenged planners to provide access to basic urban services to communities from all socio-economic groups. However, many urban communities are distinctly segregated in their access to amenities. Microtransit services are slowly filling this void for serving communities that do not generally have good access in cities.

[Spare](https://sparelabs.com/en/), in its provision of Software-as-a-Service (Saas) for the transportation industry, helps operate dozens of on-demand transportation services worldwide. As a company with a philosophy of openness and transparency that is conscious of its impact on communities and the environment, Spare is keen to quantify how its microtransit operations are changing the fabric of its partner cities. In this research, we want to determine the impact of introducing on-demand transportation on accessibility to goods and services (e.g. healthcare, education, food, shopping) (e.g. [Mayaud et al., 2019](https://www.sciencedirect.com/science/article/pii/S0198971519303813)), develop methods to better visualize and communicate the positive and negative impacts/tradeoffs of introducing on-demand transportation in certain regions (e.g. Nicoletti et al, 2021), and examine the equity impacts of on-demand transportation, by associating modal shifts and travel behaviour changes with socio-demographic variables (e.g. [Marquet, 2020](https://www.sciencedirect.com/science/article/pii/S0264275120312749?casa_token=La7ZN6Bd3uUAAAAA:9KZbq7M-uLdyB_dFoVWy_nM1oAWCmwv-o9W-m7cmc7B2b9RQC7aCvKMp0V__RC8pGub8KDNZ3w)). Spare will provide high-resolution trip data (anonymised and suitably redacted for privacy purposes) from key transit agencies in a variety of cities and countries.

<br />

### 2. Sensing urban demographics using alternate sources of satellite imagery, street view or social media data.

Geocoded socio-economic data is fundamental for urban planning. From research on human migration to equity-driven studies, spatial socio-economic data helps in understanding complex social patterns in cities. Most of the time, comprehensive socio-economic data at small spatial scales is provided by census programs such as the American Community Survey, the Canadian Census, or The Hague Cijfers. Census data, however, has strong limitations, three main ones being that (1) it is recorded every 5 or 10 years, (2) the process of gathering, processing, and making the data available is costly, labour-intensive and affects the digital privacy of citizens, and (3) census data detailed enough to be useful for planners/researchers is only available for a select group of western countries (e.g. the United States, Canada, Australia, New Zealand). This makes it difficult for planners in many cities in the world to develop policies that appropriately reflect the needs and realities of the communities they serve. Not surprisingly, this has a disproportionate impact on communities that are already underrepresented, to begin with (i.e. indigenous communities, racial minorities, refugees, etc).

In this project, the student will find an alternative way of sensing socio-economic attributes within cities using sources of data which may have originally been developed for different purposes, e.g. satellite imagery, street level (i.e. Google Street View), etc. These sets could be used to train a "Socio-Demographic" model that could accurately classify city blocks into socio-economic categories (e.g. income, education, rent, population density, building age, etc). Data collected from social media (i.e. Twitter, Facebook, Linkedin etc.) could also be used. The availability of granular census data in countries like the United States and Canada would allow training, calibrate and test the accuracy of the model on a large number of cities. Such a model could offer valuable insights for planners in many cities without socio-economic data being available.

<br />

### 3. Use and validation of location mapping services (Google Maps, OpenStreetMaps, etc) for urban research.

Open-source data (Google, OpenStreetMap, etc) is used for fine-grain mapping of land use, the environmental impact of activities, liveability measures, disasters and socio-demographic analysis in cities. Among open and user-generated data, Google seems to be the most complete and comprehensive with almost 90% data spatially validated ([Deng, 2017](https://dl.acm.org/doi/10.1145/3152178.3152182)). Where data is unavailable, such services use machine learning algorithms to detect socio-economic attributes of neighbourhoods in cities. These algorithms are often biased and leave out, or poorly sense communities that may be data-poor.

The student will carry out an extensive comparison of google data versus open street maps (and maybe more location-based datasets) and identify ways of validating the sets with empirical data of observation. They will estimate the bias in both data concerning socio-demographic metrics of neighbourhoods ([Arribas-Bel, D. 2019](https://journals.sagepub.com/doi/abs/10.1177/0042098018779554)) to speak to the richness or poverty of such location-based services and its use in urban research.

<br />

### 4. Investigating the socio-technical interplay between human mobility behaviour and digital infrastructure (like Google Maps).

A large part of human mobility behaviour is mediated by physical mobility infrastructure that is represented in digital infrastructure (DI). However, DI is not a neutral representation of the physical world, rather it comes with its own set of assumptions and biases about human behaviour. Digital representations of infrastructure such as Google Maps tend to provide highly biased perspectives of the geographic world to users. Our research suggests that using Google Maps in an urban environment will result in users misinterpreting the information given by Google Maps (e.g., an urban drive often involves end-to-end parking time as well not included in Google Maps suggestions), leading them to make decisions that they would not otherwise make. This typically leads users of Google Maps to prefer driving over public transport more than individuals that have not used Google Maps. Similar biased perspectives have also been observed in other multi-modal mapping and routing software. We believe that these biased perspectives could have a considerable effect on the modes of transportation users choose, which in turn is likely to increase the carbon emissions of those users. Such assumptions and biases can have unexpected consequences to mobility behaviour, both for users of digital infrastructure and for those who design physical infrastructure and manage mobility.

In this project, the student will develop a human-centric perspective on mobility behaviour, to better understand the socio-technical interplay between human mobility behaviour and digital infrastructure. It will also explore the consequences of this interplay for mobility management and propose modes of governance which can adequately respond to it.

<br />

### 5. Coupling scenario discovery tools of urban planning with socioeconomic processes in cities

By 2050, 80% of the world population will inhabit cities. The associated growth and development poses severe social, economic and environmental challenges for decision-makers. This outlook has nudged municipal authorities towards the promise of "smart" cities to integrate urban infrastructure with technology-mediated services, strengthen social cohesion and improve governance for citizen engagement ([Nam & Pardo, 2011](https://dl.acm.org/doi/10.1145/2037556.2037602)). Although policies promoting intelligent services (e.g. mobility, health and energy) provide opportunities for many, they contribute to a widening socioeconomic gap among the citizenry. On the one hand, decisions are fragmented among many stakeholders who struggle to address complex and competing priorities, and on another, algorithms bias against citizens who are vulnerable and not directly involved in decision-making ([Ertner, 2011](https://pure.itu.dk/portal/en/publications/five-enunciations-of-empowerment-in-participatory-design(0e97bee0-24dd-405f-b865-4d6773c76b24).html)).

In this project, the student will develop a generative design tool for supporting decision-makers in planning citizen-centred urban areas (neighbourhoods, cities and regions). Specifically, the student will build a data-driven model of an urban area that integrates core components of infrastructure (buildings, streets, amenities and open spaces) and networked material and energy flows. Then, use large census datasets to identify the socioeconomic conditions of people and couple the generative design tool with the dynamics of socioeconomic and/or environmental change ([Meerow, 2015](https://onlinelibrary.wiley.com/doi/full/10.1111/jiec.12252?casa_token=46DxMvg5o_gAAAAA%3ALb7aOJ4krG0aO0xzml_66hZR9I8BBvRokXEG3zZTDIQx6o8FBdaZ5Gz2LUCgJeTnjYxAs2iQqvU98GE)). Using machine-learning, they will develop methods to explore millions of design options, assessing the long-term social, economic and environmental consequences of decisions for different urban communities.

<br />

### 6. Estimating the disproportionate impact of COVID-19 in India

COVID-19 has proven to be one of the deadliest pandemics in history. Our policymakers have
diminished the consequences and impacts of varied measures to mere models and numbers. Schools
have shut down for months, crime and abuse have risen and millions of people have lost their jobs. In
India, multiple communities of migrant labourers, minorities and children have disproportionately
been affected by the pandemic. It is imperative to find where our policy measures are needed most,
and how to implement them, to reduce the disproportionate impact on life and work of countless
families across the country.

The primary goals of this project are to (1) identify the socio-economic composition of communities affected by COVID-19 across India, and (2) compare the characteristics of these communities based on their geography and socio-economic indicators. Open-source COVID-19 data that tracks the spread of the disease in India has been curated by the [Development Data Lab](http://www.devdatalab.org/covid). The student will obtain publicly available region-level data from the source above (demographics, health indicators, etc.) and combine with COVID-19 case counts at the region-level. They can use state-wide policy data (if available), to understand and correlate the trends in case numbers. Socio-economic data of India can be found from the same lab [here](http://www.devdatalab.org/shrug).

<br />

### 7. Cities for citizens: actively engaging citizens in co-creation of public policy for urban planning.

By 2050, 80% of the world population will inhabit cities. The associated growth and development poses severe social, economic and environmental challenges for decision-makers. This outlook has nudged municipal authorities towards the promise of "smart" cities to integrate urban infrastructure with technology-mediated services, strengthen social cohesion and improve governance for citizen engagement ([Nam & Pardo, 2011](https://dl.acm.org/doi/10.1145/2037556.2037602)). Although policies promoting intelligent services (e.g. mobility, health and energy) provide opportunities for many, they contribute to a widening socioeconomic gap among the citizenry. On the one hand, decisions are fragmented among many stakeholders who struggle to address complex and competing priorities, and on another, algorithms bias against citizens who are vulnerable and not directly involved in decision-making ([Ertner, 2011](https://pure.itu.dk/portal/en/publications/five-enunciations-of-empowerment-in-participatory-design(0e97bee0-24dd-405f-b865-4d6773c76b24).html)).

The student will explore the intersection of deliberative and computational methods for studying the effectiveness of mediating
or stimulating valuable citizen participation ([Arnstein, 1969](https://www.tandfonline.com/doi/abs/10.1080/01944366908977225)) in public policy and urban planning.

<br />

### 8. Evaluating the impact of diverse social values in building an accessible and inclusive city.

Achieving inclusion and fairness in policy interventions within cities has become a central objective for urban planners around the world. Modern cities have challenged planners to provide access to basic urban services to communities from all socio-economic groups. However, many urban communities are distinctly segregated in their access to amenities. Urban management and planning focus widely on improving or developing infrastructure that has a significant contribution to the overall delivery of services for an urban area. Such an approach, however, is traditionally based on a utilitarian principle where the aim is to maximize the benefits to all citizens. Using a utilitarian principle often risks exacerbating inequalities as it is blind to the distribution of the benefit.

To understand and address this issue, the student will develop an equity-based framework that compares the differences between different socially-driven policy for urban areas. A case of accessibility to amenities or environmental impacts of consumption patterns can be used for such an analysis.
