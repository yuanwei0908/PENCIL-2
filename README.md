# PENCIL
A Modular Pytorch Implementation of Probabilistic End-to-end Noise Correction for Learning with Noisy Labels

# Introduction

[PENCIL](https://arxiv.org/abs/1903.07788) is a recent method for training vision models under label noise. I built this implementation in order to have a modular version of PENCIL which can be easily integrated with other training strategies. Big thanks to the authors and their official implementation (https://github.com/yikun2019/PENCIL) which was used as a starting point.

# Requirements

# Usage

* *main.ipynb* contains the core script needed to train and validate on CIFAR
* *pencil.py* contains the loss function and learning rate controls proposed in the PENCIL paper which may be integrated into other training settings.
