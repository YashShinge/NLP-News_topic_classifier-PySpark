### [News topic classifier in PySpark](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5765572329082963/819669162567595/1062157151406693/latest.html)

This repo contains an NLP project with the primary goal of classifying news based on its title, into 4 categories:
1. Business
2. Science and Tech
3. Entertainment
4. Health

I would recommend you to go through my databricks notebook (.dbc exported as .html) which can be found [here](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5765572329082963/819669162567595/1062157151406693/latest.html), as it preserves the display format which gets disrupted when exported as an .ipynb notebook (as seen in the jupyter notebook in this repo).


The dataset used is from UCI ML Repo, and can be found [here](http://archive.ics.uci.edu/ml/datasets/News+Aggregator).  
This project is done in PySpark.
Concepts and libraries of NLP are used for processing the data.
Being a multiclass-classification problem, Naïve Bayes classifier was used, and an accuracy of over 92% was achieved.

