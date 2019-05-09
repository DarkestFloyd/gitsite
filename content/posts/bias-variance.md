+++ 
draft = true
date = 2019-05-08T15:12:56-04:00
title = "Bias variance tradeoff  (Coming soon..)"
description = "hello world"
slug = "" 
tags = ["machine-learning"]
# categories = ["Visually Explained"]
externalLink = ""
series = []
+++


In this post, I would like to explain some what the Bias Variance tradeoff is and try to do so
with visualizations that would aid understanding.

In the machine learning literature, the bias and variance tradeoff is heavily used when trying to pick a model that generalizes well, while being able to predict well. 

The BV problem, in my head, is simply put as - finding a model that would generalize well (low variance) while having good predictive power (low bias). To understand what and how this works, it is worth taking a moment to understand how we define bias and variance. A handdy math equation, which you would have undoubtable seen in many textbooks [cite..] is below:

What does this mean?

<svg id="d3chart"></svg>

<script src="https://d3js.org/d3.v5.js"></script>
<script src="../../scripts/bias-variance.js"></script>

