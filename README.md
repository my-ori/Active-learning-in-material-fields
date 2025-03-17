# Active learning in material fields
## This code is related to the journal article: https://doi.org/10.1007/s00339-024-07728-9
### Abstract

Machine learning (ML) has found widespread applications in predicting material properties and mechanical behaviors across various scales in computational materials science. This data-driven approach typically relies on large datasets to train predictive models. However, labeling data samples through numerical simulations in materials science can be computationally intensive. In response to this challenge, this research delves into the utilization of active learning (AL) strategies to selectively label the most informative data samples for regression and classification models. Additionally, Several novel AL strategies were developed to enhance the development of probabilistic ML models. Through illustrative examples, this study demonstrated that AL could significantly boost ML training efficiency by labeling only a small subset of data samples while achieving exceptional model performance.

## Repository Structure

This repository contains both deterministic and probabilistic models, all of which can be run using Jupyter Notebook. The required datasets are also provided.

The training data consists of 1D molecular chain mechanical responses under varying temperatures and deformation gradients.

## 1. Deterministic Models

The deterministic folder includes active learning methods for both classification and regression:

1. Classification: 
Uncertainty Sampling
2. Regression:
Greedy Sampling (GS)
Greedy Sampling on the Output (GSO)
Improved Greedy Sampling (IGS)











Both the deterministic and probabilistic are uploaded. The code can be run on the Jupyter Notebook. The needed data are uploaded as well. 
In this repository, the training data is 1D molecular chain mechanical response under different temperatures and deformation gradients. In the deterministic folder, the active learning methods include both classification and regression. The classification method we used in this paper is uncertainty sampling and the regression method we used is the Greedy Sampling (GS) and its variations Greedy Sampling on the Output (GSO) and Improved Greedy Sampling (IGS). In the probabilistic folder, there are three active learning methods. One is GS, and other two proposed methods called GSO-KL and IGS-KL, here KL is the metric to quantify the difference between two distributions. 


Any problems when running the code, feel free to contact the author: Yingbin Chen, yingbin-chen@uiowa.edu

