# A Bayesian framework for Convolutional Neural Networks using Stochastic Gradient Hamiltonian Monte Carlo

This project we formulate a Bayesian framework for Convolutional Neural Networks using Stochastic Gradient Hamiltonian Monte Carlo(SGHMC)



Link to report here: [link](https://github.com/interactivetech/BayesianCNN-SGHMC.git)

This repository implements a Bayesian CNN framework using SGHMC. We compare our method to MC-Dropout. Experiments and models were developed using Tensorflow and Edward. 

Abstract:

Convolutional Neural Networks(CNN's) are powerful image processing models that have no estimates of uncertainty. (Gal & Ghahramani, 2015) developed efficient estimation of CNN's weight uncertainty using variational approximation. Although this method is promising, variational approximation is known to underestimate the true distribution and does not fit well on multi-modal distributions (Gal & Ghahramani, 2015). The purpose of this study is to explore better inference methods, such as Stochastic Gradient Hamiltonian Monte Carlo, to better approximate model posterior of Convolutional Neural Networks architectures and improve class label prediction.

#ToDo

1. Conducting model criticism by analyzing the posterior predictive distribution. Tutorial here: http://edwardlib.org/tutorials/criticism

One check would be a PPC: Posterior predictive checks (PPCs) analyze the degree to which data generated from the model deviate from data generated from the true distribution. 

For more interesting links of probabalistic inference:
Look at the Edward Library:http://edwardlib.org/
Bayesian Method for Hackers: https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers
