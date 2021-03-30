Statistical Modeling with R and Stan
================
Denis Cohen  
<denis.cohen@mzes.uni-mannheim.de>

## Abstract

Statistical models are widely used in the social sciences for
measurement, prediction, and hypothesis testing. While popular
statistical software packages cover a growing number of pre-implemented
model types, the diversification of substantive research domains and the
increasing complexity of data structures drive persistently high demand
for custom modeling solutions. Implementing such custom solutions
requires that researchers build their own models and use them to obtain
reliable estimates of quantities of substantive interest. Bayesian
methods offer a powerful and versatile infrastructure for these tasks.
Yet, seemingly high entry costs still deter many social scientists from
fully embracing Bayesian methods.

To push past these initial hurdles and to equip participants with the
required skills for custom statistical modeling, this two-day workshop
offers an advanced introduction to statistical modeling using R and
Stan. Following a targeted review of the underlying mechanics of
generalized linear models and core concepts of Bayesian inference, the
course introduces participants to Stan, a platform for statistical
modeling and Bayesian statistical inference. Participants will get an
overview of the programming language, the R interface RStan, and the
workflow for Bayesian model building, inference, and convergence
diagnosis. Applied exercises provide participants with the chance to
write an run various model types and to process the resulting estimates
into publication-ready graphs.

## Prerequisites

Working knowledge of the software environment `R` as well as working
knowledge of (generalized) linear models is required for participation
in this course. Basic knowledge of linear algebra and probability theory
is recommended.

This workshop requires installations of recent versions of
[`R`](https://cran.r-project.org/mirrors.html) and
[`RStudio`](https://rstudio.com/products/rstudio/download/#download). On
Day 2 of the workshop, we will use [`Stan`](https://mc-stan.org/) via
its R interface `RStan`. Setting up `RStan` can be somewhat
time-consuming as it requires the installation of a C++ compiler.
Workshop participants should follow [these
instructions](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started)
on the Stan Development Team’s GitHub to install and configure the
[`rstan`](https://cran.r-project.org/web/packages/rstan/index.html)
package and its prerequisites on their operating system *before the
workshop*. Should you encounter problems, feel free to send me an email.

# Course Structure

The workshop consists of six sessions of up to 120 minutes each. Each
session starts with a lecture-style input talk, followed by lab-style
applied exercises.

| Session | Topics                                                                                                      |
| :-----: | :---------------------------------------------------------------------------------------------------------- |
|    1    | **R Math & Programming Refresher**                                                                          |
|         | 1. Good coding practices                                                                                   |
|         | 2. Object types and conversions; slicing and indexing                                                      |
|         | 3. Control structures                                                                                      |
|         | 4. Probability distributions                                                                               |
|         | 5. Linear algebra                                                                                          |
|    2    | **Generalized Linear Models**                                                                               |
|         | 1. GLM basics: Systematic component, link function, family/likelihood                                      |
|         | 2. The simulation approach                                                                                 |
|         | 3. Quantities of interest (definition, calculation, simulation)                                            |
|    3    | **Bayesian Fundamentals**                                                                                   |
|         | 1. Fundamental concepts: Prior distribution, likelihood, posterior distribution                            |
|         | 2. MCMC Algorithms                                                                                         |
|    4    | **Applied Bayesian Statistics Using Stan: Basics**                              |
|         | 1. Stan: Language, documentation, and core program blocks                                                  |
|         | 2. The Bayesian workflow                                                                                   |
|    5    | **Applied Bayesian Statistics Using Stan: Extensions**                  |
|         | 1. Optional Stan program blocks: Functions, transformed data, transformed parameters, generated quantities |
|         | 2. Efficiency tuning                                                                                       |
|         | 3. Processing posterior draws in Stan and R                                                                |
|    6    | **Applied Bayesian Statistics Using Stan: Advanced Modeling**                                               |


## About the Instructor

Denis Cohen is a postdoctoral fellow in the Data and Methods Unit at the
[Mannheim Centre for European Social Research
(MZES)](https://www.mzes.uni-mannheim.de/), [University of
Mannheim](https://www.uni-mannheim.de/), co-organizer of the [MZES
Social Science Data
Lab](https://www.mzes.uni-mannheim.de/socialsciencedatalab/page/events/),
and co-editor of the blog [Methods
Bites](https://www.mzes.uni-mannheim.de/socialsciencedatalab/). His
research focus lies at the intersection of political preference
formation, electoral behavior, and political competition. His
methodological interests include quantitative approaches to the analysis
of clustered data, measurement models, data visualization, strategies
for causal identification, and Bayesian statistics.