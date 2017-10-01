# Prosodic Features from Large Corpora of Child-Directed Speech as Predictors of the Age of Acquisition of Words

This repository contains code and data for the Ridge Regression analyses presented in the paper "Prosodic Features from Large Corpora of Child-Directed Speech as Predictors of the Age of Acquisition of Words (ArXiv preprint, 2017)"

## Data
The data folder contains word type-level prosodic features (derived from the [Brent](http://childes.talkbank.org/access/Eng-NA/Brent.html) and [Providence](http://phonbank.talkbank.org/access/Eng-NA/Providence.html) 
corpus, respectively) for a set of 600 target words (from the [wordbank](http://wordbank.stanford.edu/) project. 

## Code
The three jupyter notebooks contain python code for prosody feature analysis (egemap_prosody_feature_analysis.ipnb); language model-derived feature analysis (srilm_features_analysis.ipnb); and ridge regression models for predicting the age of acquisition of words using egemap prosody (experiment 1 in the paper) features and language model-derived features (experiment 3 in the paper) (python_regression.ipnb).


<!-- This code requires [Torch7](http://torch.ch/) and [nngraph](http://github.com/torch/nngraph).  -->
<!-- It is updated to use torch version around May 2016. Minimum preprocessing is needed to obtain a good accuracy, including lower-casing and tokenization. -->

## Citation
```
@article{frermann:frank:2017,
  author = {Lea Frermann and Michael C. Frank},
  title = {Prosodic Features from Large Corpora of Child-Directed Speech as Predictors of the Age of Acquisition of Words},
  year={2017},
  journal = "arXiv preprint cs.CL/1709.09443"
}

```
