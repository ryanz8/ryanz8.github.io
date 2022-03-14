---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Permutation-Invariant Representation of Neural Networks with Neuron Embeddings
**Authors**: **Ryan Zhou**, Christian Muise, Ting Hu

**Venue**: To appear in EvoStar 2022

**Abstract**: Neural networks are traditionally represented in terms of their weights. A key property of this representation is that there are multiple representations of a network which can be obtained by permuting the order of the neurons. These representations are generally not compatible between networks, making recombination a challenge for two arbitrary neural networks - an issue known as the "permutation problem" in neuroevolution. This paper proposes an indirect encoding in which a neural network is represented in terms of interactions between neurons rather than explicit weights, and which works for both fully connected and convolutional networks. In addition to reducing the number of free parameters, this encoding is agnostic to the ordering of neurons, bypassing a key problem for direct weight-based representation. This allows us to transplant individual neurons and layers into another network without accounting for the specific ordering of neurons. We show through experiments on the MNIST and CIFAR-10 datasets that this method is capable of representing networks which achieve comparable performance to direct weight representation, and that combining networks this way preserves a larger degree of performance than through direct weight transfer.

You can download the paper [here](/files/NeuronEmbedding.pdf).

## Prediction Intervals of Machine Learning Models for Taxi Trip Length
**Authors**: Ella Morgan, **Ryan Zhou**, Wenying Feng

**Venue**: International Conference on Applied Mathematics, Modeling and Computational Science (AMMCS) 2019

**Abstract**: Errors are always present in predictions produced by machine learning models. Producing a quantitative estimate of the uncertainty in a model’s output is crucial for many fields, especially those where predictive models drive important decisions. In this paper we discuss two methods for producing prediction intervals for neural network, random forest, and gradient boosted tree models. We then evaluate the prediction intervals produced by each algorithm by predicting the expected ride length for a NYC taxi trip dataset. We show that inductive conformal prediction produces the most reliable intervals for all machine learning models investigated.

## Estimating Energy Forecasting Uncertainty for Reliable AI Autonomous Smart Grid Design
**Authors**: Maher Selim, **Ryan Zhou**, Wenying Feng, Peter Quinsey

**Venue**: Energies, Volume 14 (2021)

**Abstract**: Building safe, reliable, fully automated energy smart grid systems requires a trustworthy electric load forecasting system. Recent work has shown the efficacy of Long Short-Term Memory neural networks in energy load forecasting. However, such predictions do not come with an estimate of uncertainty, which can be dangerous when critical decisions are being made autonomously in energy production and distribution. In this paper, we present methods for evaluating the uncertainty in short-term electrical load predictions for both deep learning and gradient tree boosting. We train Bayesian deep learning and gradient boosting models with real electric load data and show that an uncertainty estimate may be obtained alongside the prediction itself with minimal loss of accuracy. We find that the uncertainty estimates obtained are robust to changes in the input features. This result is an important step in building reliable autonomous smart grids.

## Reducing Error Propagation For Long Term Energy Forecasting Using Multivariate Prediction
**Authors**: Maher Selim, **Ryan Zhou**, Wenying Feng, Omar Alam

**Venue**: International Conference on Computers and Their Applications (CATA) 2020

**Abstract**: Many statistical and machine learning models for prediction make use of historical data as an input and produce single or small numbers of output values. To forecast over many timesteps, it is necessary to run the program recursively. This leads to a compounding of errors, which has adverse effects on accuracy for long forecast periods. In this paper, we show this can be mitigated through the addition of generating features which can have an “anchoring” effect on recurrent forecasts, limiting the amount of compounded error in the long term. This is studied experimentally on a benchmark energy dataset using two machine learning models LSTM and XGBoost. Prediction accuracy over differing forecast lengths is compared using the forecasting MAPE. It is found that for LSTM model the accuracy of short term energy forecasting by using a past energy consumption value as a feature is higher than the accuracy when not using past values as a feature. The opposite behavior takes place for the long term energy forecasting. For the XGBoost model, the accuracy for both short and long term energy forecasting is higher when not using past values as a feature.

