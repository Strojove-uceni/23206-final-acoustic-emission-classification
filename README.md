# Optimizing the Drill - Acoustic Emission Classification

This repository contains the final project for the Machine Learning 2 course at FNSPE, 2023.

### Authors: Barbora Bumbálková, Jan Zavadil

Please open AE_classificatio_demo.ipynb to see our results. Detailed training flow of neural networks along with the development and optimization process can be seen on [WandB](https://wandb.ai/hzavadil98) page as well as the full training scripts.

## Abstract

The goal of this project is to find an automated, reliable and cheap method to monitor the level of sharpness of a drill in a manufacturing line in order to facilitate optimal replacement of worn bits. The chosen approach relies on the phenomenon of acoustic emission - the process of solid materials emmiting ultrasound waves during irreversible structural changes. Acoustic emission (AE) signals are measured with sensors on the surface of an object of interest during drilling, the level of drill sharpness is also recorded. In our setup, we measured AE signals with five different levels of drill sharpness, which led us to formulate a simple classification machine learning task with five classes. We deployed multiple neural network architectures relying on 1D convolutional layers to perform the featurization of measured signals followed by a fully connected network performing the classification. All classification methods implemented surpassed the results of non DNN based clyssifiers, the best classifying with accuracy of over 87%.


