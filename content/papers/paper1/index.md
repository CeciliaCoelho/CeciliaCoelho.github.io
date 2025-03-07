---
title: "Neural Chronos ODE: Modelling bidirectional temporal patterns in time-series data" 
date: 2025-02-12
tags: ["Machine Learning", "Neural ODEs", "Forecasting Future", "Unveiling Past", "Neural Chronos ODE"]
author: ["C. Coelho","M. Fernanda P. Costa", "L.L. Ferrás"]
description: "This work introduces Neural Chronos Ordinary Differential Equations (Neural CODE), a deep neural network architecture that fits a continuous-time ODE dynamics for predicting the chronology of a system both forward and backward in time. Published in Expert Systems with Applications, 2025." 
summary: "This work introduces Neural Chronos Ordinary Differential Equations (Neural CODE), a deep neural network architecture that fits a continuous-time ODE dynamics for predicting the chronology of a system both forward and backward in time. Published in Expert Systems with Applications, 2025." 
cover:
    alt: "Neural Chronos ODE"
    relative: false
editPost:
    URL: "https://www.sciencedirect.com/science/article/abs/pii/S0957417425004063?via%3Dihub"
    Text: "Expert Systems with Applications"

---

---

##### Download

+ [Paper](neuralCODE.pdf)
+ [Code and data](https://github.com/CeciliaCoelho/NeuralChronosODE)

---

##### Abstract

This work introduces Neural Chronos Ordinary Differential Equations (Neural CODE), a deep neural network architecture that fits a continuous-time ODE dynamics for predicting the chronology of a system both forward and backward in time. To train the model, we solve the ODE as an initial value problem and a final value problem, similar to Neural ODEs. We also explore two approaches to combining Neural CODE with Recurrent Neural Networks by replacing Neural ODE with Neural CODE (CODE-RNN), and incorporating a bidirectional RNN for full information flow in both time directions (CODE-BiRNN). Variants with other update cells namely GRU and LSTM are also considered and referred to as: CODE-GRU, CODE-BiGRU, CODE-LSTM, CODE-BiLSTM.
Experimental results demonstrate that Neural CODE outperforms Neural ODE in learning the dynamics of a spiral forward and backward in time, even with sparser data. We also compare the performance of CODE-RNN/-GRU/-LSTM and CODE-BiRNN/-BiGRU/-BiLSTM against ODE-RNN/-GRU/-LSTM on three real-life time-series data tasks: imputation of missing data for lower and higher dimensional data, and forward and backward extrapolation with shorter and longer time horizons. Our findings show that the proposed architectures converge faster, with CODE-BiRNN/-BiGRU/-BiLSTM consistently outperforming the other architectures on all tasks, achieving a notably smaller mean squared error—often reduced by up to an order of magnitude
---

---

##### Citation

Coelho, C., M. Fernanda P. Costa, and L. L. Ferrás. "Neural Chronos ODE: Modeling bidirectional temporal patterns in time-series data." Expert Systems with Applications (2025): 126784.

```BibTeX
@article{COELHO2025126784,
title = {Neural Chronos ODE: Modelling bidirectional temporal patterns in time-series data},
journal = {Expert Systems with Applications},
volume = {273},
pages = {126784},
year = {2025},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2025.126784},
url = {https://www.sciencedirect.com/science/article/pii/S0957417425004063},
author = {C. Coelho and M. Fernanda P. Costa and L.L. Ferrás},
keywords = {Neural Networks, Time-series, Neural ODE, Forecasting future, Unveiling past, Neural CODE, Numerical methods},
}
```

---
