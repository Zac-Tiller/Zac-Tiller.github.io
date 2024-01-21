---
layout: post
title:  "MEng Thesis - Introducing Dynamic Skew Variance-Mean Mixture Processes"
date:   2023-09-23 09:00:00 +0
categories: masters research
permalink: '/masters-thesis/'
---

## "Non-Gaussian Stochastic Processes for Financial & Tracking Applications: Introducing Dynamic Skew Variance-Mean Mixture Processes"


#### Lucky enough to be supervised by Prof. Simon Godsill, we applied Particle Filters to Levy process driven state space equations, to model time series. Specifically, we looked at financial time series as often these display non-Gaussian statistical properties. Using Levy processes as the driving stochastic noise meant we could capture observed statistical properties in the data, such as skew and kurtosis, something not possible with using Guassian noise.

#### Stepping away from a Gaussian driven process made closed-form inference intractable, so an advanced statistical signal processing technique was required; sequential Monte Carlo methods, or Particle Filters.

#### We made improvements on existing [literature](https://arxiv.org/abs/1912.12524) by expanding the capability of the 'Levy State Space Model' to track and notice changes in the skew of the driving noise of the time series quicker. Thus we present a new class of models, called **Dynamic Skew Variance-Mean Mixture Processes**.

#### Success was found filtering high frequency and low frequency financial data, for various FX pairs (including USD/JPY) where metrics measuring predictive capacity were higher than the models that don't have the extra skew-tracking capability. For a bit of fun, we also extended the model to 2-Dimensions, and used it to track football (soccer) player position on the pitch!


#### If this is interesting to you, feel free to reach out via email for the paper!