---
title: "Causal inference for semicompeting risks and beyond"
collection: talks
permalink: /talks/2024semicompeting
type: "Talk"
venue: "University of Michigan"
date: 2024-10-22
location: "Ann Arbor, Michigan, USA"
---

[Slides](../files/2024semicompeting.pdf)

Semi-competing risks refer to the phenomenon where a primary event (such as mortality) can "censor" an intermediate event (such as relapse of a disease), but not vice versa. Under the multi-state model, the primary event consists of two specific types: the direct outcome event and an indirect outcome event developed from intermediate events. Within this framework, we show that the total treatment effect on the cumulative incidence of the primary event can be decomposed into three separable pathway effects, capturing treatment effects on population-level transition rates between states. We next propose two estimators for the counterfactual cumulative incidences of the primary event under hypothetical treatment components. The first estimator is the generalized Nelson-Aalen estimator with inverse probability weighting under covariates isolation and completely random censoring. The second estimator is based on the efficient influence function with weaker assumptions. The asymptotic properties of these estimators are established. The first estimator only involves a propensity score model and avoids modeling the cause-specific hazards. The second estimator has robustness against the misspecification of submodels.
