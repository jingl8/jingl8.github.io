---
permalink: /
title: "Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am PhD candidate (ABD) in political science at UIUC, my research interests are in the use of computational and statistical methods to study important substantive questions related to mass political behavior and political economy in the American and comparative contexts. I have done research projects on dynamic modelling of mass partisan polarization and segregation, machine learning model evaluation for binary classification tasks, the contextual and temporal variation of individuals' attitudes towards globalization, A Lasso-augmented time series alternative to the synthetic control method, bootstrap standard errors for matching estimators,  meta-analysis as a multiple hypothesis testing problem, etc. I am on the academic job markert. 

Publication
======

**Area under the ROC Curve has the Most Consistent Evaluation for Binary Classification** PLOS ONE

**Abstract**: The proper use of model evaluation metrics is important for model evaluation and model selection in binary classification tasks. This study investigates how consistent different metrics are at evaluating models across data of different prevalence while the relationships between different variables and the sample size are kept constant. Analyzing 156 data scenarios, 18 model evaluation metrics and five commonly used machine learning models as well as a naive random guess model, I find that evaluation metrics that are less influenced by prevalence offer more consistent evaluation of individual models and more consistent ranking of a set of models. In particular, Area Under the ROC Curve (AUC) which takes all decision thresholds into account when evaluating models has the smallest variance in evaluating individual models and smallest variance in ranking of a set of models. A close threshold analysis using all possible thresholds for all metrics further supports the hypothesis that considering all decision thresholds helps reduce the variance in model evaluation with respect to prevalence change in data. The results have significant implications for model evaluation and model selection in binary classification tasks. ([Link](https://doi.org/10.1371/journal.pone.0316019))

Selected Working Paper Abstracts
======

Paper 1: **A computational model of the geography of mass partisan polarization** (Under Review)

**Abstract**:  Both partisan polarization and partisan segregation are phenomena of great concern in the US in recent decades. Existing research that looks at mass partisan polarization and geography in conjunction focuses exclusively on the extent of partisan geographical sorting but neglects the substantial effect geographical context can have on the formation of mass partisan polarization. This paper shows that while partisan geographical sorting can happen to a certain extent, it only happens in spaces where there is a certain level of partisan segregation to start with. In essence, geographical context’s effect on partisan polarization is more substantial than partisanship’ effect on geographical sorting, a surprising result given current literature’s focus on the latter rather than the former.

Paper 2: **Are we bootstrapping the right thing? A new approach to quantify uncertainty of ATT Estimates** (Under Review)

**Abstract**: This paper proposes a new non-parametric bootstrap method to quantify the uncertainty of average treatment effect estimate for the treated from matching estimators. More specifically, it seeks to quantify the uncertainty associated with the average treatment effect estimate for the treated by bootstrapping the treatment group only and finding the counterpart control group by pair matching on estimated propensity score without replacement. We demonstrate the validity of this approach and compare it with existing bootstrap approaches through Monte Carlo simulation and analysis of a real world data set. The results indicate that the proposed approach constructs confidence intervals and standard errors that have 95 percent or above coverage rate and better precision compared with existing bootstrap approaches, while these measures also depend on percent treated in the sample data and the sample size. ([arxiv Preprint](https://arxiv.org/abs/2310.11683)).
