---
title: Assessment
linktitle: Assessment
toc: true
type: docs
date: "2019-05-05T00:00:00Z"
draft: true
menu:
  epa1316-2020:
    name: Assessment
    weight: 90

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---

<a name="assessment"></a>

## Assessment

The final mark for the course is composed of the following three components:

* [Contribution to module's discussion forum](#forum) (5%)
* [Assignment 1](#task_01) (20%)
* [Assignment 2](#task_02) (25%)
* [Assignment 3](#task_03) (50%)

Assignments 1 and 2 are described below. Students should keep in mind the following information regarding the submission of assignments:

* **Submission is electronic only** and will be managed through Turnitin.
* Assignments will be prepared in the Jupyter Notebook file format and then converted into a self-contained HTML file that will then be submitted on Turnitin.


<a name="marking_criteria"></a>

### Marking Criteria

This course follows the standard marking criteria (the general ones and those relating to GIS assignments in particular) set by the School of Environmental Sciences. In addition to these generic criteria, the following specific criteria relating to the code provided will be used:

* **0-15**: the code does not run and there is no documentation to follow it.
* **16-39**: the code does not run, or runs but it does not produce the expected outcome. There is some documentation explaining its logic.
* **40-49**: the code runs and produces the expected output. There is some documentation explaining its logic.
* **50-59**: the code runs and produces the expected output. There is extensive documentation explaining its logic.
* **60-69**: the code runs and produces the expected output. There is extensive documentation, properly formatted, and explaining its logic.
* **70-79**: all as above, plus the code design includes clear evidence of skills presented in advanced sections of the course (e.g. custom methods, list comprehensions, etc.).
* **80-100**: all as above, plus the code contains novel contributions that extend/improve the functionality the student was provided with (e.g. algorithm optimizations, novel methods to perform the task, etc.).

<a name="forum"></a>

### **Discussion forum**

* Type: `Coursework`
* Continuous assessment
* 5% of the final mark
* NO chance to be reassessed
* Electronic submission only.

Students are encouraged to contribute to the online discussion forum set up for the module. The contribution to the discussion forum is assessed as an all-or-nothing 5% of the mark that can be obtained by contributing *meaninfully* to the online discussion board setup for the course. *Meaningful* contributions include both questions and answers that demonstrate the student is committed to make the forum a more useful resource for the rest of the group.

<a name="task_01"></a>

### **Assignment 1**

* Type: `Coursework`
* 1h.
* Date: **Thursday, October 24th-2019** (Week 5).
* 20% of the final mark
* Chance to be reassessed
* In-lab electronic submission.

This assessment will consist of an in-lab computer test with multi-option
and short answer questions covering topics introduced in lectures and labs
1-4. More details will be provided during class in advance.

<a name="task_02"></a>

### **Assignment 2** - In-lab computer test II

* Type: `Coursework`
* 1h.
* Date: **Friday, November 21st-2019** (Week 9).
* 25% of the final mark
* Chance to be reassessed
* In-lab electronic submission.

This assessment will consist of an in-lab computer test with multi-option
and short answer questions covering topics introduced in lectures and labs
5-9. More details will be provided during class in advance.

<a name="task_03"></a>

### **Assignment 3** - *Targetting areas*

* Type: `Coursework`
* [Equivalent to 2,500 words] Three maps/tables, code and 750 words.
* 50% of the final mark
* Chance to be reassessed
* Final Assessment
* Due on **Thursday, December 5th-2019** (Week 11).
* Electronic submission only. Static HTML with NO interactive cells.

In this assignment, you will take the role of a real-world data scientist tasked to identify areas to direct investments. You are consulting for the City of Liverpool on a program to target investments towards particularly disadvantaged areas that are nevertheless popular or have the potential to become so. The Economic Development division knows that only five local super output areas (LSOAs) will be funded but would like to know which ones.

Develop a data strategy, deploy it, and present the results in a rigorous but intuitive fashion, together with the code.

**Minimum requirements** (complete *all*)

* Combine *at least two* datasets, potentially among those used in the course.
* Employ *at least two* techniques from the set of analytics covered in the course.
* Justify why you have chosen the methods you use and how they help you answer the question at hand. Critically discuss their limitations too.
* Provide a list of the top five areas that you recommend be funded for improvement.
* Explain clearly how you have arrived at the list and how the decision has been informed by the data analysis and the methodologies employed.
* Include documented code that demonstrate programming understanding of the student.

**Suggestive paths** (optional)

* Combine a LISA analysis of deprivation with kernel density maps of Twitter activity to identify areas of high values at both.
* Combine several relevant variables into a geodemographic analysis to obtain candidate areas and display the results in an aesthetically pleasant choropleth.

**Data**

This assignment can use any of the [datasets]({{site.baseurl}}/datasets.html) employed in the course, and/or any other datasets you consider useful. If you are thinking of including additional datasets, or have ideas in this respect, please get in touch with the module lead ([Trivik Verma](mailto:T.Verma@tudelft.nl)).
