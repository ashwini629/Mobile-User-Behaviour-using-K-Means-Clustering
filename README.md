# Mobile User Behaviour using-K-Means Clustering
Objective

Analyze mobile user behaviour to segment users using K-Means Clustering. This enables better user understanding, targeted marketing, and product personalization.

Dataset

user_behavior_dataset.csv includes:

User ID: Unique Identifier

Age: User age

Gender: Male / Female

Device Model: Phone model used

Data Usage (MB/day): Monthly data usage in MB

Number of Apps Installed: Number of installed apps

Exploratory Data Analysis (EDA) 

Age: Users mainly between 20–35.

Data Usage: Two major groups – casual vs heavy users.

Number of Apps Installed: Most have 10–40 apps.

Categorical Analysis

Female users tend to install slightly more apps.

Device model usage varies by age group.

Bivariate Insights

Younger users use more data and apps.

Positive correlation between data usage and apps installed.

K-Means Clustering

Elbow Method

Optimal number of clusters: 4

Cluster Profiles

Cluster

Age Range

Data Usage (MB)

Apps Installed

Description

0

20–30

High (~2000 MB)

High (30–40)

Power users

1

35+

Low (~300 MB)

Low (<20)

Low engagement / older users

2

25–40

Moderate

Medium

Average users

3

Teens

Moderate-High

High

Young tech-savvy explorers

Visualization Summary

PCA Scatter Plot: Clear cluster separation

Boxplots: Revealed outliers in data usage

Heatmap: Moderate positive correlation between usage and installed apps

Tools Used

Python, Pandas, Matplotlib, Seaborn

Scikit-learn (KMeans, StandardScaler, PCA)
