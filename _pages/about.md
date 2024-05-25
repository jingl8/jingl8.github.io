---
permalink: /
title: "Welcome to my academic page"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am PhD candidate (ABD) in political science at UIUC, my research interests are in statistical and computational methods, and substantively in comparative politics and political economy. I have done research projects on boostrap standard errors for matching estimators, model evaluation metrics for binary classification tasks, the contextual and temporal variation of individuals' attitudes towards globalization, A Lasso-agumented alternative to synthetic control method: estimating the effect of Hong Kong's sovereignty return to China, meta-analysis as a multiple hypothesis testing problem, etc.  Please feel free to reach out.

Working Paper Abstracts
======

Paper 1: **Are we bootstrapping the right thing? A new approach to quantify uncertainty of ATT Estimates**

**Abstract**: This paper proposes a new non-parametric bootstrap method to quantify the uncertainty of average treatment effect estimate for the treated from matching estimators. More specifically, it seeks to quantify the uncertainty associated with the average treatment effect estimate for the treated by bootstrapping the treatment group only and finding the counterpart control group by pair matching on estimated propensity score without replacement. We demonstrate the validity of this approach and compare it with existing bootstrap approaches through Monte Carlo simulation and analysis of a real world data set. The results indicate that the proposed approach constructs confidence intervals and standard errors that have 95 percent or above coverage rate and better precision compared with existing bootstrap approaches, while these measures also depend on percent treated in the sample data and the sample size ([Link](https://arxiv.org/abs/2310.11683)).

Paper 2: **Data Imbalance and the Use of Binary Classification Performance Metrics**

**Abstract**: This paper examines a critical question in the application of machine learning models in the social sciences, namely the use of model evaluation metrics for binary classification tasks. More specifically, it investigates how sample data imbalance as measured in prevalence level affects the values of various
confusion matrix performance metrics including TPR, TNR, PPV, NPV, balanced accuracy, Bookmaker informedness, F1 score and Matthew’s correlation coefficient as well as the commonly used accuracy and Area Under the ROC Curve measures. The results indicate that the accuracy measure is dominated by the majority class as data become more imbalanced. The balanced accuracy (as well as bookmaker informedness) and Matthew’s correlation coefficient take model performance on both classes of cases into account. The F1 score, meanwhile, has a monotonically increasing relationship with prevalence level. These trends of the confusion matrix performance metrics hold regardless of which specific type of model is used for making predictions. The results have significant implications for applications of machine learning models in the field.
([Link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4530905))

