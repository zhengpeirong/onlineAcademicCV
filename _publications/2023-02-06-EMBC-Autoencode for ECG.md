---
title: "Yuchen Jiang, *Peirong Zheng* (co-first author), Dakun Lai, A Semi-supervised Algorithm for Atrial Fibrillation Attack Prediction Using Convolution Auto-encoder of Time Series Signal."
collection: publications
excerpt: 'This paper primarily builds upon the experiments I conducted as part of my undergraduate research project, under the guidance of my supervisor, Dakun Lai. Additionally, the writing of this paper was mainly completed by Yuchen Jiang.'
date: 2023-02-06
venue: 'the 45th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC)'
paperurl: 'https://zhengpeirong.github.io/onlineAcademicCV/files/EMBC23_0485_MS.pdf'
---
[Download paper here](https://zhengpeirong.github.io/onlineAcademicCV/files/EMBC23_0485_MS.pdf)

Abstract—At the beginning of the attack, atrial fibrillation
(AF) usually presents as paroxysmal atrial fibrillation (PAF),
and may be further transformed into persistent AF that may
cause high-risk diseases such as ischemic stroke and heart
failure. Under considerations of current machine learning
algorithms for AF predictions that manure extraction of
features and tag electrocardiograph (ECG) data are time
consuming and labor-intensive processes, a novel two-stages of
semi-supervised algorithm for AF attack prediction is proposed
in this paper. With the input of the time series signal of RR
interval, the first stage is designed as an unsupervised learning
based on convolution auto-encoder (CAE) network and the
second stage is a supervised learning based on Long short-term
memory (LSTM) model. A total of 855,882 heartbeat activities
including 30 segments of PAF and 30 segments of normal heart
rate were collected so as to evaluate the performance of the
CAE-LSTM combination model. The obtained results showed
that the averaged accuracy and the root mean square error
(RMSE) of ten-fold cross-validation are 90.16% and 0.0113,
respectively. In summary, the preliminary results suggested that
the combination of the unsupervised CAE model and of the
supervised LSTM model could reduce the dimension of the
input data meanwhile perform the subsequent classification
with a small amount of labeled data as input. Moreover, the
proposed algorithm could be useful to predict AF when the
sample is scarce, and potentially prevent the occurrence of a
paroxysmal atrial fibrillation.
