---
title: "Graph Neural Network Architecture Search"

date: "2023-01-01"

links:
  github: "https://github.com/rezanmz/GNN-NAS"
---

This project's purpose is to optimise hyper-parameter tuning of graph neural networks in a large search space. To speed up the process, we first search a low-resolution version of the training graph, then increase the network's quality on a zoomed-in version of the same graph. The search is done using Optuna.
