# Amazon-Reviews-EDA-and-Helpfulness-Classification-Model-PySpark-Code-and-Presentation

This repository contains the code used in an analysis of Amazon reviews, as well as a review helpfulness prediction model. 
Over 3 million reviews were accessed via Spark (Databricks, Azure) to synthesize insights on customers' rating and reviewing habits. Some interesting insights: 1-star reviews are found more helpful than 5 star reviews. Earlier reviews of a product tended to be more helpful than later reviews. 20% of reviewers showed 0 rating variability across all their reviews (only reviewers with a min. of 5+ reviews were considered) - always rewarding 5 stars. For a full list of insights, please refer to the slide deck found within this repository.

#Files

1. Review Habits Trend Analysis. This code contains EDA and data-querying to mine for descriptive insights into customer's reviewing habits. Code is primarily written in SQL and  PySpark. Additionally contains code for a k-means clustering of review sizes.

2. Kaggle Modelling. This code contains the process for the review helpfulness prediction model. It leverages significant data manipulation (cleasing and feature engineering) and various manually-tested algorithms in its machine learning pipeline.

3. Topic Modelling. This code features review LDA topic modelling using a variety of NLP preprocessing techniques.
