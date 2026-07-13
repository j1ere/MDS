# Improving Wine Quality Analysis Through Dimensionality Reduction

## Business Background

A wine manufacturing company produces thousands of batches every year.

For every batch, laboratory tests measure several chemical properties before the wine is released to customers.

The company already records:

| Feature              | Meaning                       |
| -------------------- | ----------------------------- |
| Fixed acidity        | Amount of tartaric acid       |
| Volatile acidity     | Acetic acid concentration     |
| Citric acid          | Citric acid concentration     |
| Residual sugar       | Sugar left after fermentation |
| Chlorides            | Salt content                  |
| Free sulfur dioxide  | Preservative                  |
| Total sulfur dioxide | Total preservative            |
| Density              | Density of wine               |
| pH                   | Acidity                       |
| Sulphates            | Mineral salts                 |
| Alcohol              | Alcohol percentage            |

After tasting, experts assign a quality score from 0–10.

## The Business Problem

The company has accumulated years of production data

Unfortunately: 
* Engineers cannot visualize relationships among the wines because there are 11 features
* Marketing wants to identify groups of similar wines
* Quality control wants to detect unusual batches before shipment
* Management wants dashboards that are easy to interpret

**with 11 dimensions, no one can simply 'look' at the data**

## Business objective
* - Develop a 2 dimensional representation of wines that preserves as much useful information as possible so that
similar whines appear close together, enabling visualization, clustering, anomaly detection, and quality analysis.

## Success Cretaria
At the end of the project, we want to answer the following questions:
* Do high quality wines naturally form clusters?
* can we indentify poor-quality wines  visually?
* Are there distinct families of wines?
* Is PCA or MDA better for helping quality-control engineers understand the production process?
* Can the reduced data be used effectively for clustering?
