# NISER

## Paper data and code

This is the code for the Paper: [NISER: Normalized Item and Session Representations to Handle Popularity Bias](https://arxiv.org/pdf/1909.04276.pdf). We have implemented our methods in **Pytorch**.

Here are two datasets we used in our paper. After downloaded the datasets, you can put them in the folder `datasets/`:

- YOOCHOOSE: <http://2015.recsyschallenge.com/challenge.html> or <https://www.kaggle.com/chadgostopp/recsys-challenge-2015>

- DIGINETICA: <http://cikm2016.cs.iupui.edu/cikm-cup> or <https://competitions.codalab.org/competitions/11161>

There is a small dataset `sample` included in the folder `datasets/`, which can be used to test the correctness of the code.

## Requirements

- Python 3
- PyTorch 1.8.1

## Reimplementation Performance
> Hit@20: 53.34

> MRR@20: 18.99