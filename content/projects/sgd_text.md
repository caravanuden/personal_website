---
title: "Predicting sustainable development indices from geolocated text"
date: 2021-12-15
draft: false
slug: sgd-text
toc: true
tags: [nlp, logistic-regression, neural-network, embedding, hpo]
---

**tl;dr**:
In this project, we leverage readily-available natural language data, scraped from Wikipedia, to predict localized indices (asset, sanitation, women's education) relevant to the UN's Sustainability Goals. We explore the impact of different text embedding extraction methods and model architectures on performance in this small data task. We explore logistic regression models, feedforward DNNs, and NLP-CNNs. We use geolocated and extracted “relevant” sentence embeddings to achieve ROC-AUC scores of 0.80 (logistic regression model), 0.70 (logistic regression model), and 0.81 (feedforward DNN model) for asset, sanitation, and women's education index classification, respectively.

I performed exploratory data analysis, NLP "targeted" embedding generation, logistic regression implementation, hyperparameter optimization, and evaluation, and simple feedforward neural network implementation, hyperparameter optimization (with ray-tune), and evaluation.

- [Github repo](https://github.com/caravanuden/sdg-text)
- [Project paper](https://github.com/caravanuden/sdg-text/blob/main/CS329P_Final_Project_Paper.pdf)
