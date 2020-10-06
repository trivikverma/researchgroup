---
title: Assessment
linktitle: Assessment
toc: true
type: docs
date: "2020-08-08"
draft: false
menu:
  epa1316-2020:
    name: Assessment
    weight: 100

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---

The course is designed to include two types of assessments:

1. **Formative** : These are `ungraded` and are intended to a) fill gaps in knowledge for those who have not had any programming experience before and b) to serve as a refresher to those who wish to update their skills. The formative components of the course are:

    * [8 In-Class Labs]({{< relref "labs.md" >}}): During the scheduled lab-hours on Wednesday, you can work through the interactive Jupyter Notebooks with TAs available to help you and answer your questions. I advise you to go through these notebooks before and prepare a set of questions you want to discuss with your TA in class.
    * [8 Peer-Reviewed Homework Questions]({{< relref "labs.md" >}}): A set of homework questions will follow the In-Class Lab sessions to further consolidate your understanding. To enable peer-learning, you have the option to give and receive **Peer-Feedback** for these questions through the [Peer](https://peer.tudelft.nl/) system on developed by TU Delft scientists at EWI. This is neither graded nor obligatory. However, written peer feedback [enhances](https://educationaltechnologyjournal.springeropen.com/articles/10.1186/s41239-016-0017-y) student learning.
    * [Discussion Sessions]({{< relref "discussions.md" >}}): Every Friday you will participate in an online discussion session with your peers to discuss assigned readings. This session will be moderated by a TA in a group of 10-20 students each. The papers that you will read for each week will come along with a set of questions that will guide your reading and subsequent discussions. These papers complement the topic discussed that week in lectures and tested in assignments, therefore you are strongly encouraged to participate. The concepts covered in these sessions will also shape your ideas for the Final Group Project.

2. **Summative** : These are `graded` components and contribute to the final mark for the course as follows:

    * Assignment 01 (15%)
      - {{% staticref "epa1316-2020/assignments/assignment-01/assignment-01.zip" "newtab" %}}assignment-zip{{% /staticref %}}
      - {{% staticref "epa1316-2020/assignments/assignment-01/assignment-01.html" "newtab" %}}assignment-html{{% /staticref %}}
    * Assignment 02 (15%)
      - {{% staticref "epa1316-2020/assignments/assignment-02/assignment-02.zip" "newtab" %}}assignment-zip{{% /staticref %}}
      - {{% staticref "epa1316-2020/assignments/assignment-02/assignment-02.html" "newtab" %}}assignment-html{{% /staticref %}}
    * * Assignment 02 (10%)
      - {{% staticref "epa1316-2020/assignments/assignment-03/assignment-03.zip" "newtab" %}}assignment-zip{{% /staticref %}}
      - {{% staticref "epa1316-2020/assignments/assignment-03/assignment-03.html" "newtab" %}}assignment-html{{% /staticref %}}
    * [Final Project](#final_proj) (60%)

### Marking Criteria for assignments

The following specific criteria relating to the code provided will be used:

| Criteria                                                                                                        	| Indicative weight 	| (0-0.5)                                                                                                                                                              	| (1-1.5)                                                                                                                                                                                           	| (2)                                                                                                                                                                                                                                          	|
|-----------------------------------------------------------------------------------------------------------------	|-------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Output                                                                                                          	| 0.5                 	| the code does not run/seem to be runnable* (in case of html files) * if your syntax is wrong or data paths are messy / not reproducible (e.g. not using os.getcwd()) 	| the code runs but does not produce the expected output                                                                                                                                            	| the code runs and produces the expected output                                                                                                                                                                                               	|
| Formatting                                                                                                      	| 0.5                 	| code is not formatted at all or messy* * variables are used before they are defined, functions are used unnecessarily.                                               	| code is properly formatted*  * each section describes one aspect in a logical order and the code structure is readable (for reference see how labs are formatted with markdown and code sections) 	| - code is properly formatted.. + - variables and functions are named well.                                                                                                                                                                   	|
| Methods (e.g. Tidy Data, EDA, Graphical Excellence, Spatial Autocorrelation, Network Weights, Regression, etc.) 	| 2                 	| code/output shows no evidence of methods presented in class and homework exercises                                                                                   	| code/output shows some evidence of methods presented in class and homework exercises                                                                                                              	| code/output illustrates clear evidence of methods presented in class and homework exercises                                                                                                                                                  	|
| Documentation (Markdown/Comments)                                                                               	| 2                 	| there is no documentation to follow your code. there is no documentation to follow your code. (e.g. why did you drop a certain variable or why did you choose one over another?)                                                                                                                       	| there is some documentation explaining your code’s logic and your choices in the analysis but these choices or logic is not clear.                                                                	| there is extensive documentation explaining your code’s logic and your choices in the analysis.  - no hypothesis present, if one was explicitly asked for 	|

### Submission

Deadlines for everything will be Friday at 2330 for the week's homework or assignments. The first week's homework deadline is Monday 7th Sep at 2330.

  * In-Class Labs: labs are not for submission. They help you practice and understand python programming in this course.
  * Peer-Reviewed Homework Questions: Submit weekly homework exercises called hw-0x.ipynb as follows,
    - login to [Peer](https://peer.tudelft.nl/) with your TU Delft credentials.
    - find the course ``Introduction to Urban Data Science``
    - enroll in the course
    - complete the exercises each week
    - zip the file into <yourfullname-0x.zip>. For example, I would send my file as **trivikverma-04.zip for week 4's exercise**.
    - submit the corresponding week's exercise to Peer in the respective assignment. FGor example, to Homework-1 for week 1.
    - wait for instructions on reviewing your peer's work and then reviewing the feedback you got from your peer.
    - **Note**: this is a double-blind peer review, so please do not add your names or any information revealing your identity in the submission files.
  * Graded Assignments: Submit assignments on Brightspace. Formats and naming conventions are given within the .ipynb files.
