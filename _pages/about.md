---
permalink: /
title: "Welcome to my academic page, I am here to help!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student majoring in political science at UIUC, my research interests are in statistical and computational methods, and substantively in comparative and international political economy. I have written research papers on boostrap standard errors for matching estimators, class imbalance's effect on model performance metrics for binary classification tasks, the contextual variation of individuals' attitudes towards globalization, empirical comparision of synthetic control versus interrupted time series design, meta-analysis as a multiple hypothesis testing problem, etc.  

Research Paper Abstracts
======

Paper 1: **Are we bootstrapping the right thing? A new approach to quantify uncertainty of ATT Estimates**

**Abstract**: This paper proposes a new non-parametric bootstrap method to quantify the uncertainty of average treatment effect estimates from matching estimators. More specifically, it seeks to quantify the uncertainty associated with the treatment effect variation  for the treated group by bootstrapping the treatment group only and finding the counterpart control group by matching on estimated propensity score. We demonstrate the validity of this approach and compare it with the existing approaches through Monte Carlo simulation and real world example data. The results indicate that the proposed approach achieves comparable precision and coverage rate as existing bootstrap approaches but may produce more precise standard error estimates with lower coverage rate depending on the proportion of treatment group units in the sample data and the specific matching method used.([Paperlink](https://arxiv.org/abs/2310.11683))

Paper 2: **Data Imbalance and the Use of Binary Classification Performance Metrics**

**Abstract**: This paper examines a critical question in the application of machine learning models in the social sciences, namely the use of performance metrics for model evaluation of binary classification tasks. More specifically, it investigates how sample data imbalance as measured in prevalence level affects the values of various
confusion matrix performance metrics including TPR, TNR, PPV, NPV, balanced accuracy, Bookmaker informedness, F1 score and Matthew’s correlation coefficient as well as the commonly used accuracy and Area Under the ROC Curve measures. The results indicate that the accuracy measure is dominated by the majority class as data become more imbalanced. The balanced accuracy (as well as bookmaker informedness) and Matthew’s correlation coefficient take model performance on both classes of cases into account. The F1 score, meanwhile, has a monotonically increasing relationship with prevalence level. These trends of the confusion matrix performance metrics hold regardless of which specific type of model is used for making predictions. The results have significant implications for applications of machine learning models in the field.
([Paperlink](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4530905))

Paper 3: **Estimating the economic effect of Hong Kong’s sovereignty return to China: comparing Synthetic Control Method and Interrupted Time Series Design**

**Abstract**: Interrupted time series design and the synthetic control method are both commonly used empirical strategies to establish causal evidence for the effect of certain interventions or treatments in time. This paper offers an empirical comparison of these two methods by estimating the economic effect of Hong Kong's sovereignty return to China. While both methods leverage the potential outcome framework, the underlying assumptions made about the counterfactual states are different between these two methods. The interrupted time series design construct post-intervention counterfactual by linear extrapolation from a prediction model estimated from the pre-intervention outcome trajectory. The synthetic control method meanwhile tries to make the synthetic control unit mimic the entire pre-intervention outcome trajectory of the unit subject to an intervention. Analysis results presented in this paper show that when linear extrapolation of pre-intervention outcome measures is a bad approximation of counterfactual outcome, interrupted time series design could construct the wrong counterfactual state and give misleading causal effect estimate of an intervention of interest, while the synthetic control method offers more robust causal estimates in these scenarios.

