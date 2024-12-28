---
layout: single
title: "Understanding Logistic Regression in Social Statistics"
date: 2024-12-27
categories: [statistics, regression]
tags: [logistic regression, R, social statistics]
author: Mohsen Monji
excerpt: "A brief introduction to logistic regression and its applications in social statistics, with examples in R."
---

### Introduction

Logistic regression is a statistical method used for modeling binary outcomes, such as:

- Predicting whether an individual is diagnosed with anxiety or not.
- Examining disparities in employment status.

It’s widely used in social science research for understanding and predicting categorical outcomes.

---

### Example in R

Here’s how to run a simple logistic regression in R:

```r
# Load the library
library(tidyverse)

# Sample data
data <- tibble(
  outcome = c(1, 0, 1, 0),
  predictor = c(5, 3, 8, 6)
)

# Logistic regression
model <- glm(outcome ~ predictor, data = data, family = binomial)
summary(model)
