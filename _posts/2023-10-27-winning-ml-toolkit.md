---
title: "Best ML toolkit: Consensus from the ML community"
date: 2023-10-27
permalink: /posts/winning-ml-toolkit/
tags:
  - AI
  - Machine Learning
  - Tabular data
  - Time-series
  - Competitions
---

For this blog post, I'll focus on tabular and time-series data since this is the most common data type that data scientists face and has the highest applicability. To supplement my takeaways on best practice for tabular data, I'll also draw on the findings from MLcontest's State of Competitive Machine Learning Report published earlier this year and share the consensus "winning" toolkit for machine learning (ML) competitions.

As mentioned in my previous post, However, I still believe using the consensus of the ML community acts as a useful starting point. As it is very easy to get bogged down by analysis paralysis when there are thousands of models, tools, and packages to choose from.

- Winning toolkit (core)
  - PyData (python, NumPy, pandas, SciPy, Scikit-learn)
  - Visualisation (matplotlib and seaborn)
  - Deep learning (PyTorch) - used in 77 to 96% of winning solutions from 2021 to 2022
    - Most used PyTorch directly, but some used pytorch-lightning and fastai, which are built ontop PyTorch
  - GBT (XGBoost, LightGBM, CatBoost)
  - Hyperparameter tuning - #Optuna
    - [Optuna](https://optuna.org/) is a hyperparameter optimisation library which can be used with any modelling framework - including PyTorch, scikit-learn, XGBoost, LightGBM, and others. It makes it easy to efficiently search for the optimal hyperparameters, and takes care of parallelisation. While Optuna isn’t the only library which can do this, it was very clearly the most popular in 2022 — with around 10% of all winning solutions importing it, and 30% of winners who did any kind of hyperparameter optimisation using it. (61% of winners did manual hyperparameter optimisation, and the remainder used either genetic algorithms or a custom automated hyperparameter tuning approach)
    logseq.order-list-type:: number
  - Experiment tracking - Weights & biases
    - mlflow (databricks) for open source alternative
- [Optuna](https://optuna.org/) is a hyperparameter optimisation library which can be used with any modelling framework - including PyTorch, scikit-learn, XGBoost, LightGBM, and others. It makes it easy to efficiently search for the optimal hyperparameters, and takes care of parallelisation. While Optuna isn’t the only library which can do this, it was very clearly the most popular in 2022 — with around 10% of all winning solutions importing it, and 30% of winners who did any kind of hyperparameter optimisation using it. (61% of winners did manual hyperparameter optimisation, and the remainder used either genetic algorithms or a custom automated hyperparameter tuning approach)
  logseq.order-list-type:: number
