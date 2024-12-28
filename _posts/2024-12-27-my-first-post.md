---
layout: single
title: "Logistic Regression"
date: 2024-12-27
categories: [statistics, regression]
tags: [logistic regression, R, social statistics]
author: Mohsen Monji
excerpt: "A brief introduction to logistic regression and its applications in social statistics, with examples in R."
math: true
---

### Introduction

Logistic regression is a statistical method used for modeling binary outcomes, such as:

- Predicting whether an individual is diagnosed with anxiety or not.
- Examining disparities in employment status( employed versus unemployed)

It’s widely used in social science research for understanding and predicting dischotomous outcomes.

---

### Logistic Regression Formula

Logistic regression equation is expresses as follows:

<p>$$
P(Y = 1) = \frac{1}{1 + e^{-(\beta_0 + \beta_1X)}}
$$</p>

Where:

- <p>\( Y \)</p>: Binary outcome variable  
- <p>\( X \)</p>: Predictor variable  
- <p>\( \beta_0, \beta_1 \)</p>: Model coefficients  

---

### Example in R

Here’s how to run a simple logistic regression in R:

```r
# Load necessary library
library(tidyverse)

# Sample data
data <- tibble(
  outcome = c(1, 0, 1, 0),
  predictor = c(5, 3, 8, 6)
)

# Logistic regression
model <- glm(outcome ~ predictor, data = data, family = binomial)
summary(model)
```

The glm() function in R fits a generalized linear model, with the family = binomial argument specifying logistic regression.

