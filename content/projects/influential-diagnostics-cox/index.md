---
title: "Robust Influential Diagnostics for Semi-Parametric and Stratified Survival Models"
date: 2016-02-28
summary: "Development and validation of a robust influential diagnostics approach for Cox proportional hazards and stratified survival models, addressing masking effects through simulation studies and real-world data analysis."
tags:
  - stat
featured: true
status: "Completed"
role: "Researcher"
duration: "2013-2015"
team_size: 1
highlights:
  - "Proposed a robust influential diagnostics method for Cox and stratified survival models"
  - "Mitigated masking effects in high-dimensional and correlated data settings"
  - "Extensive simulation studies across varying sample sizes and model configurations"
  - "Validated methodology using real-world healthcare data"
---

## Overview

Influential observations can substantially distort parameter estimation and inference in survival models, particularly in semi-parametric frameworks such as the Cox proportional hazards model. Identifying such observations is therefore critical to ensure model robustness and reliability.

This project focused on developing a **robust and sensitive influential diagnostics approach** that improves the detection of influential points, particularly in scenarios where conventional methods may fail due to **masking effects**.

## Methodological Contributions

### Limitations of Existing Approaches

Traditional diagnostics methods in survival analysis include:
- Score residuals
- Scaled score residuals
- Likelihood displacement
- Lmax statistics

While widely used, these approaches may fail to detect influential observations when multiple influential points exist simutaneously, leading to **masking**, where their effects obscure each other.

### Proposed Approach

A novel influential diagnostics method was developed to:
- Improve sensitivity in detecting influential observations
- Reduce masking effects in the presence of multiple influential points
- Maintain robustness across different model specifications, including stratified Cox models

The method was designed within the semi-parametric framework, ensuring compatibility with commonly used survival analysis models.

## Simulation Study

A comprehensive simulation study was conducted to evaluate the performance of the proposed method under controlled conditions.

Key design factors included:
- **Sample size variation** (small to large cohorts)
- **Different censoring rates**
- **Varying effect sizes and covariate structures**
- **Multiple influential observation scenarios**

The proposed method was systematically compared with existing diagnostics approaches to assess:
- Detection accuracy
- Sensitivity to influential points
- Robustness under masking conditions

## Real-World Validation

To ensure practical applicability, the method was validated using **real-world healthcare data**, demonstrating its ability to:
- Identify influential observations in clinical datasets
- Improve model reliability
- Support more robust statistical inference in applied settings

## Key Contributions

- Development of a **robust influential diagnostics framework** for survival models
- Comprehensive detection of influential observations under **masking scenarios**
- Comprehensive evaluation through both **simulation and real-world data**
- Contribution to enhancing **model reliability in biomedical research**

## Publication

This work resulted in a peer-reviewed publication:

- *An alternative identification of influential points in Cox proportional hazards model*
  International Journal of Applied Mathematics and Statistics (2015)

## Impact

This research strengthens the reliability of survival analysis by improving the identification of influential observations. The proposed methodology is particularly relevant for:
- Biomedical and clinical studies
- Real-world healthcare data analysis
- High-dimensional and heterogeneous datasets

By addressing limitations in conventional diagnostics, this work contributes to more **robust and interpretable statistical modelling** in applied research.

---

**Status**: Completed
