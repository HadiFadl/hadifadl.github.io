---
layout: post
title: 'Context-aware big data quality assessment: a scoping review'
published: true
date: '2023-06-13'
image: /assets/img/avatar-research.jpg
external_url: 'https://doi.org/10.1145/3603707'
tags:
  - big data
  - data quality
  - context awareness
  - research
subtitle: ACM Journal of Data and Information Quality
---
The term data quality refers to measuring the fitness of data regarding the intended usage. Poor data quality leads to inadequate, inconsistent, and erroneous decisions that could escalate the computational cost, cause a decline in profits, and cause customer churn. Thus, data quality is crucial for researchers and industry practitioners.
Different factors drive the assessment of data quality. Data context is deemed one of the key factors due to the contextual diversity of real-world use cases of various entities such as people and organizations. Data used in a specific context (e.g., an organization policy) may need to be more efficacious for another context. Hence, implementing a data quality assessment solution in different contexts is challenging.
Traditional technologies for data quality assessment reached the pinnacle of maturity. Existing solutions can solve most of the quality issues. The data context in these solutions is defined as validation rules applied within the ETL (extract, transform, load) process, i.e., the data warehousing process. In contrast to traditional data quality management, it is impossible to specify all the data semantics beforehand for big data. We need context-aware data quality rules to detect semantic errors in a massive amount of heterogeneous data generated at high speed. While many researchers tackle the quality issues of big data, they define the data context from a specific standpoint. Although data quality is a longstanding research issue in academia and industries, it remains an open issue, especially with the advent of big data, which has fostered the challenge of data quality assessment more than ever.
This paper provides a scoping review to study the existing context-aware data quality assessment solutions, starting with the existing big data quality solutions in general and then covering context-aware solutions. The strength and weaknesses of such solutions are outlined and discussed. The survey showed that none of the existing data quality assessment solutions could guarantee context awareness with the ability to handle big data. Notably, each solution dealt only with a partial view of the context. We compared the existing quality models and solutions to reach a comprehensive view covering the aspects of context awareness when assessing data quality. This led us to a set of recommendations framed in a methodological framework shaping the design and implementation of any context-aware data quality service for big data. Open challenges are then identified and discussed.
