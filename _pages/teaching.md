---
layout: page
permalink: /teaching/
title: Teaching & Tutorials
description: Open course materials, step-by-step tutorials with code, and the courses I have taught.
nav: true
nav_order: 2
---

## Open course materials

Free, self-paced materials on research data management and statistical modeling, created under the *InDepth Data Science Consulting* label and shared under a CC-BY license. They are built with Quarto, are fully reproducible and come with companion files on the Open Science Framework.

{% include figure.liquid loading="eager" path="assets/img/InDepth_Logo_hex.png" alt="InDepth logo" class="img-fluid" max-width="140px" %}

| Module | What you will learn |
| --- | --- |
| [Setup R, RStudio and repositories](https://daniel-manrique.quarto.pub/rdm-datascience/R-studioRepositories.html) | A reproducible working environment with R, Python, Git and GitHub. |
| [Research data management](https://daniel-manrique.quarto.pub/rdm-datascience/RDM/RDM-index.html) | Why RDM matters, organizing files and tables, working with images, and sharing data following FAIR principles. |
| [Principles of statistical modeling](https://daniel-manrique.quarto.pub/rdm-datascience/Modeling/Modeling-index.html) | Handling data tables, exploratory analysis, fitting models and checking their diagnostics. |

[Open the full course site](https://daniel-manrique.quarto.pub/rdm-datascience/) &middot; [OSF materials](https://osf.io/cngt3/) &middot; [Source on GitHub](https://github.com/indepth-data/DataScience_Teaching)

For hands-on guides with code, see the [tutorials](#tutorials) below.

## Tutorials

Practical guides that I publish on [Towards Data Science](https://towardsdatascience.com/author/damanrique/) and [Medium](https://medium.com/@damanrique). Every guide is written as a Quarto document, so the data and code to reproduce its figures are public in the [TDS-Medium_Blog](https://github.com/daniel-manrique/TDS-Medium_Blog) repository.

### Bayesian regression with brms

- **[Beyond the Mean: Embracing Uncertainty in Measurements with Bayesian Analysis and Multilevel Modeling](https://medium.com/@damanrique/beyond-the-mean-embracing-uncertainty-in-measurements-with-multilevel-modeling-2bde9d521736)**. Multilevel models for repeated measurements. [Code](https://github.com/daniel-manrique/TDS-Medium_Blog/tree/main/articles/2024-02-03_BeyondTheMean)
- **[Do not over-think about "outliers", use a Student-t distribution instead](https://towardsdatascience.com/do-not-over-think-about-outliers-use-a-student-t-distribution-instead-b6c584b91d5c/)**. A robust alternative when extreme observations are part of your data. [Code](https://github.com/daniel-manrique/TDS-Medium_Blog/tree/main/articles/2024-02-22_OutliersStudent-t)
- **[Avoiding abuse and misuse of T-test and ANOVA: Regression for categorical responses](https://towardsdatascience.com/avoiding-abuse-and-misuse-of-t-test-and-anova-regression-for-categorical-responses-af15af53a456/)**. Ordinal regression with the cumulative family. [Code](https://github.com/daniel-manrique/TDS-Medium_Blog/tree/main/articles/2024-04-03_UseAndAbuseANOVA)
- **[Improving the analysis of object (or cell) counts with lots of zeros](https://towardsdatascience.com/improving-the-analysis-of-object-or-cells-counts-with-lots-of-zeros-f343d1430637/)**. Hurdle and zero-inflated models. [Code](https://github.com/daniel-manrique/TDS-Medium_Blog/tree/main/articles/2024-04-19_CountsZeroInflated)

### Spatial analysis of cells

- **[Introduction to spatial analysis of cells for neuroscientists (part 1)](https://towardsdatascience.com/introduction-to-spatial-analysis-of-cells-for-neuroscientists-part-1-82bef519ad46/)**. Point pattern analysis with spatstat. [Code](https://github.com/daniel-manrique/TDS-Medium_Blog/tree/main/articles/2024-05-24_SpatialAnalysis_Part1)
- **[Where a cell sits matters more than how many there are (part 2)](https://towardsdatascience.com/where-a-cell-sits-matters-more-than-how-many-there-are/)**. Raster layers and point process models for how neurons, astrocytes and microglia sit relative to each other. [Code](https://github.com/daniel-manrique/TDS-Medium_Blog/tree/main/articles/2026-10-23_SpatialAnalysis_Part2)

These guides are the practical companion of my research papers on [point pattern and topological data analysis](/publications/). The repository also holds further guides in R and Python (topological data analysis, Bayesian reanalysis of open data) that are still being prepared for publication.

### Writing on science and publishing

- [We Reward the Paper, Not the Truth: What Publish-or-Perish Teaches Young Scientists](https://medium.com/age-of-awareness/we-reward-the-paper-not-the-truth-what-publish-or-perish-teaches-young-scientists-c67b4ee2b85f)
- [What does the Dana-Farber misconduct scandal reveal about scientific integrity in the XXI century?](https://medium.com/@damanrique/what-does-the-dana-farber-misconduct-scandal-reveal-about-scientific-integrity-in-the-xxi-century-326266e42cdc)

## Courses taught

### Design and data management for research

**Doctoral program in Appliend and behavioral Neuroscience** \
**Universidad San Buenaventura (Bogotá, Colombia)** \
**Date:** March 2024 -

**Summary:** This course prepares third-year doctoral students for the precise and coherent formulation of a doctoral research project. The course develops four modules: Research Design, Data Management, Good Scholarly Practice, and Research Project Writing. In particular, this seminar equips students with the use of several web/informatic tools that strengthen their research skills and research project within the framework of open and reproducible science.

### Introduction to data analysis with R

**Lerni academy / University Duisburg-Essen (Essen, Germany)** \
**Date:** March - June, 2023

**Summary:** This course offers introductory tools for data analysis and visualization with R. In particular, the course is focused on using the [tidyverse](https://www.tidyverse.org/), [ggdist](https://mjskay.github.io/ggdist/) and [tidybayes](https://mjskay.github.io/tidybayes/) for data handling and visualization, and [brms](https://cran.r-project.org/web/packages/brms/index.html) to perform Bayesian data analysis using MCMC. The topics covered are simple lineal regression with continuous and categorical variables, the use of different families of distributions and a touch of multilevel models.

### Introduction to neuroscience

**[Escuela de astronomía de Cali (Cali, Colombia)](https://escueladeastronomiadecali.com/nosotros/)** \
**Date:** September 2023

**Summary:** This course provides and introduction to neuroscience for students of different disciplines including biology, psychology, engineering and physics. It covers basic neuroanatomy and cell biology,together with broad functional trends of the central nervous system. the course also addressees the main neuroscience fields with its research methods and challenges.

## Training for your team

I also offer workshops and consulting for faculties, institutes and companies: see [Work with me](/work-with-me/).
