---
title: "Application of Neural Networks in Multiphase Flow Through Porous Media: Predicting Capillary Pressure and Relative Permeability Curves"
collection: publications
permalink: /publication/2019-01-Journal-JPSE-1
excerpt: 'Zhi Zhong, <b>Siyan Liu</b>, Mohammad Kazemi, Timothy R. Carr. <i>Submitted to Journal of Petroleum Science and Engineering.</i>'
date: 2019-01-16
venue: 'JPSE 2019'
---
<b>Siyan Liu</b>, Arsalan Zolfaghari, Shariar Shaun Sattarin, Amirmasoud Kalantari-Dahaghi, Shahin Negahban. <i>Submitted to Journal of Petroleum Science and Engineering.</i>

## Abstract
Artificial Neural Networks (ANN) are trained to simulate two-phase capillary pressure and relative permeability data in bundles of capillary tubes with non-uniform arbitrary wettability conditions and cross-sectional shapes of different irregular convex polygons. All polygons with variable number of corners are randomly generated for a given range of inscribed radii, shape, and elongation factors. To generate the data for the training of ANNs, the minimization of Helmholtz free energy and Mayer-Stowe-Princen (MS-P) method are combined to find thermodynamically consistent threshold capillary pressures for two-phase flow. These capillary pressures are then used to 
determine the sequence of displacements in different capillary tubes. We calculate saturations and phase conductance at each quasi steady-state 
condition where no more displacements can be done for a given capillary pressure. The generated two-phase capillary pressure and relative 
permeability curves are then used for the training of ANNs. We test different design of ANNs to find the optimal workflow for the training and predicting of petrophysical properties related to multiphase flow. In this work, we present the results of two different neural network structures. In the first structure, we use ANN to predict threshold capillary pressures of different 
capillary tubes during a drainage process (i.e., oil to water displacements). In the second structure, we predict capillary pressure and relative permeability curves for an arbitrary bundle of capillary tubes. The first structure of ANNs simulates a fixed property for a given capillary tube, whereas the second structure simulates time-series data format (i.e., for a given bundle of capillary tubes calculated properties vary with saturation). To do so, we have generated multiphase flow properties for two large datasets 
consisting of 40,000 and 60,000 capillary tubes each. High-quality training datasets are critical in the training of high-fidelity ANN models. These 
models can then learn the impact of a wide variety of pore geometries (i.e., shape factors and elongations). Additionally, feature selection and 
preprocessing of the input data could significantly impact ANN's predictions. The multi-layer perceptron (MLP) neural network with three hidden layers with four outpusts is adequate for predicting capillary pressure and relative permeability curves during drainage. This model is approximately an order of 
magnitude faster than conventional direct calculations using a desktop computer with four cores CPU. Such improvement in the speed of calculations becomes significant when dealing with larger models, more dimensions, and/or 
introducing pore connectivity in 3D. 
