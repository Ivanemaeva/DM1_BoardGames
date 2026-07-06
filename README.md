# Board Games Dataset — Clustering, Classification & Pattern Mining

Data Mining 1 project (Università di Pisa, A.Y. 2025–2026) — Prof. Dino Pedreschi, Prof. Riccardo Guidotti.
Team: Fiza Naeem, Lorena Sorce, Ivane Maeva Nague.

## Overview

Full data mining pipeline applied to a board games dataset, covering data understanding, cleaning, clustering, classification, and association rule mining.

## Methods & Results

**Clustering**
- K-Means (best: silhouette score 0.579, 3 clusters)
- Hierarchical clustering (silhouette 0.603 on a 400-sample subset)
- DBSCAN (silhouette 0.088 — poor fit, discussed in report as a negative result)

**Classification**
- Decision Tree: 70.9% accuracy
- K-Nearest Neighbors: 62.4% accuracy
- Naive Bayes: 53% accuracy

**Pattern Mining**
- Apriori algorithm, 2% minimum support, rules with lift > 7

**Regression**
- Regression analysis on numerical game attributes

## Repository structure

notebooks/
├── DM1 project.ipynb          # main pipeline: data understanding & cleaning
├── Hierarchical_cluster.ipynb
├── dbscan-Clustering.ipynb
├── DT-01.ipynb                 # Decision Tree
├── K_nn_complete.ipynb         # KNN
├── NB_all_methods.ipynb        # Naive Bayes
├── patternmining.ipynb         # Apriori
├── Regression-DM.ipynb
report/
└── DM1_report.pdf

## Tech stack

Python, pandas, scikit-learn, mlxtend (association rules), matplotlib/seaborn

## Grade

30/30
