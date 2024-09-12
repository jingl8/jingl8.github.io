---
permalink: /
title: "Welcome to my academic page"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am PhD candidate (ABD) in political science at UIUC, my research interests are in the use of computational and statistical methods to study important substantive questions related to collection action and political economy both in the American and comparative contexts. I have done research projects on a dynamic model of polarization under segregation, boostrap standard errors for matching estimators, model evaluation metrics for binary classification tasks, the contextual and temporal variation of individuals' attitudes towards globalization, A Lasso-agumented alternative to synthetic control method, meta-analysis as a multiple hypothesis testing problem, etc.  Please feel free to reach out.

Paper Abstracts
======

Paper 1: **A dynamic model of polarization under segregation**

**Abstract**:  Mass partisan polarization is one of the most significant political developments in recent decades. Existing literature on partisan polarization and geographical partisan sorting focuses on digital social media’s effect on polarization and the extent of partisan motivation behind in-dividual moving and residential decisions but neglects the effect of geographical segregation on mass partisan ideological polarization. This study builds a computational model that combines classic Schelling’s segregation model and its extensions with recent polarization model. Corresponding simulation results provide ample evidence to show the dynamics of segregation’s effect on polarization and strongly support the hypothesis that higher geographical segregation makes worse mass partisan polarization. In addition, Multiscale Geographically Weighted Regression (MSGWR) on relationships between county-level partisan segregation and US presidential election results from 2000 to 2020 shows strong empirical evidence for geographical segregation’s substantial effect on mass polarization.

Paper 2: **Are we bootstrapping the right thing? A new approach to quantify uncertainty of ATT Estimates**

**Abstract**: This paper proposes a new non-parametric bootstrap method to quantify the uncertainty of average treatment effect estimate for the treated from matching estimators. More specifically, it seeks to quantify the uncertainty associated with the average treatment effect estimate for the treated by bootstrapping the treatment group only and finding the counterpart control group by pair matching on estimated propensity score without replacement. We demonstrate the validity of this approach and compare it with existing bootstrap approaches through Monte Carlo simulation and analysis of a real world data set. The results indicate that the proposed approach constructs confidence intervals and standard errors that have 95 percent or above coverage rate and better precision compared with existing bootstrap approaches, while these measures also depend on percent treated in the sample data and the sample size ([Link](https://arxiv.org/abs/2310.11683)).

Paper 3: **Area under the ROC Curve has the Most Consistent Evaluation for Binary Classification**

**Abstract**: Evaluation Metrics is an important question for model evaluation and model selection in binary classification tasks. This study investigates how consistent metrics are at evaluating different models under different data scenarios. Analyzing over 150 data scenarios and 18 model evaluation metrics using statistical simulation, I find that for binary classification tasks, evaluation metrics that are less influenced by prevalence offer more consistent ranking of a set of different models. In particular, Area Under the ROC Curve (AUC) has smallest variance in ranking of different models. Matthew's correlation coefficient as a more strict measure of model performance has the second smallest variance. These patterns holds across a rich set of data scenarios and five commonly used machine learning models as well as a naive random guess model. The results have significant implications for model evaluation and model selection in binary classification tasks. ([Link](https://doi.org/10.48550/arXiv.2408.10193))

