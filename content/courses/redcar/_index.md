---
# Course title, summary, and position in the list.
linktitle: An Example Course
summary: Learn how to use Academic's docs layout for publishing online courses, software documentation, and tutorials.
weight: 1

# Page metadata.
title: Get Started
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: true  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  redcar:
    name: REDCAR
    weight: 1
---

## Introduction

REproDucible ComputAtional Research or simply REDCAR is a project initiated by TU Delft [HumTechLab](https://www.tudelft.nl/tbm/over-de-faculteit/afdelingen/multi-actor-systems/research/humtech-lab/humtech-lab/). The goal of the project is to help students and researchers to make their computational results **reproducible**, more easily **understandable**, and **accessible to others**.

![Project idea](.gitbook/assets/project-idea.png)

## Background

Big data, powerful computers, and programming languages such as Python and R brought quantitative research to a whole new level. Now you can apply a machine learning algorithm to train a car or a drone to become automated with 2 lines of code \([proof](https://github.com/mikhailsirenko/REDCAR/blob/master/.gitbook/assets/ml.jpg)\).

Along with the opportunities, such a technological leap brought complications. Scientists became overwhelmed with all details that should be taken into account while conducting a computational study. Given the pressure from the deadlines, they are forced to **decide between "quick-and-dirty"** **and reproducible research**, not in favor of the latter. Manual corrections of the raw data, conflicting versions of software packages, lack of instructions on how the code should be executed, making it hard if not impossible to reproduce results of a computational study. As a result, more and more scholars have started to highlight the importance of **reproducibility**, propose ways to achieve it and pose it **as a minimum standard** **for assessing the value of scientific claims** \[[1](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285),[2](https://science.sciencemag.org/content/334/6060/1226)\].

But what do we mean by reproducible? In this project we will use definition introduced in \[[3](https://stm.sciencemag.org/content/8/341/341ps12.short?casa_token=VgB2iSv2JNkAAAAA:nEpwUfQh5c9LtRUjk7k3CNW99XUArjLuFcwBRgdVYUnIWHifsZLnrtxvEfCFcYk4V2yehf7Sg-LC6sA)\]:

> _"The ability to implement, as exactly as possible, the experimental and computational procedures, with the same data and tools, to obtain the same results."_

We won't talk about [_empirical_](https://www.nature.com/news/announcement-reducing-our-irreproducibility-1.12852) or [_statistical_](https://science.sciencemag.org/content/343/6168/229) reproducibility but instead [_computational reproducibility_](https://web.stanford.edu/~vcs/talks/Census2017-STODDEN.pdf) \[[4](https://aip.scitation.org/doi/abs/10.1109/MCSE.2012.82?journalCode=csx)\].

Alright. Now you understand what reproducibility is and what it's important. But what are the ways to ensure it? In short, you need to follow the rules described in \[[1](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)\], and use the tools and practices that were developed for that \(see, e.g., \[[5](https://books.google.nl/books?hl=en&lr=&id=JcmSAwAAQBAJ&oi=fnd&pg=PP1&dq=implementing+reproducible+research&ots=ym1btRtPJE&sig=tR2_-mmsrsZUwXwEHXYIrYz_HT4&redir_esc=y#v=onepage&q=implementing%20reproducible%20research&f=false)\]\). But in the REDCAR project, you'll find a bit more than that.

## REDCAR

With the REDCAR project, we're aimed at achieving more than reproducibility 😎. We realize how important is the **structure** of the study, **code formatting**, and whether it's **easily accessible** by other researchers or the general public. We translated these additional principles into 2 extra components: understandable and shared \(see Figure on top\).

Understandable here stands for how easily others can figure out that you have done. For example, if your project folder looks like [this](https://github.com/mikhailsirenko/REDCAR/blob/master/.gitbook/assets/folder-mess.png), then "Houston, we have a problem." The same holds for the code. It's much easier to reuse and modify a program that was written in compliance with coding standards. You met two variables `d = 5` and `elapsed_time_in_days = 5`. Which one is better?

If you want to share the results of your computational research, there may be no need to install Anaconda Distribution or NetLogo. Instead, you can use such instruments as [Binder Project](https://mybinder.org/), [Google Colab](https://colab.research.google.com/) or [NetLogo Web](https://netlogoweb.org/). All of them allow a person to execute the code in the cloud and therefore significantly simplify the process sharing and collaboration.

‌We linked all these 3 components into a system and supervised them with tools and practices. They are distributed across 3 workshops and can be found in the directories with corresponding names. By following the workshops in a sequential manner, you will ensure that your research a\). reproducible, b\). more easily understandable, c\). accessible to others.

```text
├── 1-reproducible
│   ├── 1.1-get-started-anaconda.md   <- Create virtual environment and example project structure
│   ├── 1.2-get-started-git.md        <- Learn the basics of Git and GitHub
│   ├── 1.3-git-jupyterlab.md         <- Setup JupyterLab extensions to make life easier
│
├── 2-understandable
│   ├── 2.1-workflows.md              <- Workflows for data science and simulation studies
│   ├── 2.2-better-code.md            <- Practice standards, conventions and common sense
│   ├── 2.3-case-study.md             <- Try it all on a case study
│
├── 3-shared
│   ├── 3.1-setup-binder.md           <- Make MyBinder.org work with your repo
│   ├── 3.2-colaboratory.md           <- Try Google Colab as an alternative
│   ├── 3.3-aws-s3.md                 <- Store your large data set on AWS servers
```

To get the maximum of the project we invite you to come and participate in the hands-on exercises. But if didn't work, get hands dirty with tutorials by yourself💪 . We tried to make them as clear possible so they can serve as cheat sheets as well. Forgot something: just open the book and follow the instructions.

## To be prepared

To participate in the workshops you will need a laptop and a couple of tools installed. The preparation process will take less than 30 minutes.

* Download and install Anaconda Distribution with Python 3.7 from here. The process is pretty straightforward: select your operating system, download installer and follow the steps. If you already have it, make sure that it works by running any script in JupyterLab \(that's the IDE that we will work in\). If you prefer to use R programming language - no problem! After installing Anaconda Distribution, open it and install RStudio. To use R in Jupyter Notebook follow this simple tutorial.
* Install Git from here. The same principle works here: select your operating system and follow the steps.
* Create a GitHub a account [here](https://github.com/join?source=header-home). Don't forget about [GitHub Student Developer Pack](https://education.github.com/pack). It provides free access and discounts to plenty of services and tools.

{% hint style="success" %}
That's it! All set now.
{% endhint %}

## Contributing & authors

We're highly interested in your opinion on the project! To contribute please, either fork it and submit a pull request, or contact us via Twitter or email.

_Mikhail Sirenko_ [@mikhailsirenko](https://twitter.com/mikhailsirenko), _Nicolas Dintzner, Jason R. Wang_ [@jasonrwang](https://twitter.com/jasonrwang) and _Trivik Verma_ [@TrivikV](https://twitter.com/TrivikV), _Bartel Van de Walle_ [@bvdwalle](https://twitter.com/bvdwalle).

## License

[BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)

## Acknowledgements

While working on this project the REDCAR project team was inspired by Cookiecutter Data Science \[[6](https://drivendata.github.io/cookiecutter-data-science/)\] made by _friendly folks at DrivenData_ , Reproducible Research module of Data Science Specialization \[[7](https://www.coursera.org/specializations/jhu-data-science)\] by _Jeff Leek_, _Roger D. Peng_ and _Brian Caffo_.

We also would like to thank _Jan Kwakkel_, _Igor Nikolic, Alexander Verbraeck_ for their input into the shaping of the project.

## References

1. Sandve GK, Nekrutenko A, Taylor J, Hovig E. Ten simple rules for reproducible computational research. PLoS computational biology. 2013 Oct;9\(10\).
2. Peng RD. Reproducible research in computational science. Science. 2011 Dec 2;334\(6060\):1226-7.
3. Goodman SN, Fanelli D, Ioannidis JP. What does research reproducibility mean?. Science translational medicine. 2016 Jun 1;8\(341\):341ps12-.
4. Stodden V. Reproducible research: Tools and strategies for scientific computing. Computing in Science & Engineering. 2012 Jul;14\(4\):11-2.
5. Stodden V, Leisch F, Peng RD, editors. Implementing reproducible research. CRC Press; 2014 Apr 14.
6. DrivenData. Cookiecutter Data Science. Available from [https://drivendata.github.io/cookiecutter-data-science/](https://drivendata.github.io/cookiecutter-data-science/) \[Accessed 03 March 2020\].
7. Coursera Inc. Data Science Specialization. Available from [https://www.coursera.org/specializations/jhu-data-science](https://www.coursera.org/specializations/jhu-data-science) \[Accessed 03 March 2020\]
