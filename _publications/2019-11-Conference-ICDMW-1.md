---
title: "An Efficient Bayesian Method for Advancing the Application of Deep Learning in Earth Science"
collection: publications
permalink: /publication/2019-11-Conference-ICDMW-1
excerpt: Dan Lu, <b>Siyan Liu</b>, Daniel Ricciuto.
date: 2019-11-01
venue: '2019 International Conference on Data Mining Workshops (ICDMW)'
paperurl: 'https://doi.org/10.1109/ICDMW.2019.00048'
---
Dan Lu, <b>Siyan Liu</b>, Daniel Ricciuto.


## Abstract
Despite their wide and successful applications, deep learning (DL) models are prone to overfitting for small training datasets, produce a poor predictive performance for uncertain data, and provide point estimations without any indication of the accuracy and credibility. These limitations of the deterministic DL models hinder their effective application in Earth system science where the labelled data are sparse, noisy and incomplete with large uncertainty and where the predictive uncertainty quantification is needed for scientific understanding and policy decision making. Integration of Bayesian inference into DL models adds an estimate of uncertainty and regularization in the predictions. However, traditional Bayesian methods are computationally unaffordable and inflexible for high-dimensional problems, which limits their application to DL systems that typically have millions of model parameters. In this effort, we propose an efficient and general-purpose Bayesian inference method to advance DL model optimization and uncertainty quantification, so as to facilitate the adoption of DL in Earth sciences. In a demonstration, we integrate the proposed Bayesian method with a feedforward neural network (NN) to build a fast-to-evaluate surrogate of the complex Energy Exascale Earth System Land Model for efficient modeling. The formulated Bayesian NN, using a small number of training data, produces an accurate prediction with high credibility, whereas with the same small training size, the deterministic NN cannot yield a reasonable estimation and does not provide confidence information. The proposed Bayesian method is computationally efficient and flexible, capable of integration with diverse network variants such as convolutional NNs and recurrent NNs to advance the application of DL in Earth sciences.

[Download paper here](https://doi.org/10.1109/ICDMW.2019.00048)
