---
layout: post
toc: true
title: "05. Econometrics"
categories: Econometrics
tags: [OLS, Estimation, Non-Linear Regression]
math: true
author:
  - Marco You
[comment]: <> (mathjax inline > \\(...\\) )
[comment]: <> (mathjax block  > $$...$$   )
[comment]: <> <p align="center"> <img src="/image/file_name.png" alt="file_name" width="460" height="260"> </p>
---

# Non-Linear Regression Functions

## 1. Introduction

Two types of non linearity in regression functions:

- Non-linear functions of a single independent varialbe (most prevailing type)
  - Polynomials
  - Logarithms
  - Interactions
  - (these 3 types are all eligible for OLS estimation)
- Regression functions that are non-linear in the parameters (only a sketch here)

We are going to study 2 groups of methods useful when

- the relation between \\(X_1\\) and \\(Y\\) depends on the value of \\(X_1\\) itself;
- the relation between \\(X_1\\) and \\(Y\\) depends on the value of \\(X_2\\)