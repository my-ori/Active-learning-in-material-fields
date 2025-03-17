# Active learning in material fields
## This code is related to the journal article: https://doi.org/10.1007/s00339-024-07728-9
## Abstract

Machine learning (ML) has found widespread applications in predicting material properties and mechanical behaviors across various scales in computational materials science. This data-driven approach typically relies on large datasets to train predictive models. However, labeling data samples through numerical simulations in materials science can be computationally intensive. In response to this challenge, this research delves into the utilization of active learning (AL) strategies to selectively label the most informative data samples for regression and classification models. Additionally, Several novel AL strategies were developed to enhance the development of probabilistic ML models. Through illustrative examples, this study demonstrated that AL could significantly boost ML training efficiency by labeling only a small subset of data samples while achieving exceptional model performance.

## Repository Structure

This repository contains both deterministic and probabilistic models, all of which can be run using Jupyter Notebook. The required datasets are also provided.

The training data consists of 1D molecular chain mechanical responses under varying temperatures and deformation gradients.

## 1. Deterministic Models

The deterministic folder includes active learning methods for both classification and regression:

1. Classification: 
 **Uncertainty Sampling**
2. Regression:
 **Greedy Sampling (GS)**
 **Greedy Sampling on the Output (GSO)**
 **Improved Greedy Sampling (IGS)**


## 2. Probabilistic Models

The probabilistic folder contains three active learning methods:

- **Greedy Sampling (GS)**
- **Greedy Sampling on the Output with Kullback-Leibler Divergence (GSO-KL)**
- **Improved Greedy Sampling with Kullback-Leibler Divergence (IGS-KL)**
  
*(KL divergence is used as a metric to quantify the difference between two probability distributions.)*

## Contact
For any issues or questions related to the code, feel free to contact the author:
- **Yingbin Chen, yingbin-chen@uiowa.edu**

