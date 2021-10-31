## (master) Pyspark ML Modelling


* [Project 1 - Searching for exotics particles in high-energy physics](#project1)
* [Project 2 - Developing a predictive model for an insurance company](#project2)

## Introduction
**1. Searching for exotic particles in high-energy physics**

* To use supervised classification algorithms to identify Higgs bosons from particle
collisions, like the ones produced in the Large Hadron Collider.
* Data set : HIGGS dataset. 2.6GB.
* Description of data set
: The data has been produced using Monte Carlo simulations. The first 21
features (columns 2-22) are kinematic properties measured by the particle
detectors in the accelerator. The last seven features are functions of the
first 21 features; these are high-level features derived by physicists to help
discriminate between the two classes.
* More info : http://archive.ics.uci.edu/ml/datasets/HIGGS

**2. Developing a predictive model for an insurance company.**

* To develop a predictive model that uses vehicle characteristics to accurately predict insurance claim payments. Such a model will allow the company to assess the potential risk that a vehicle represents.
* Data set : Each year’s worth information for insured vehicles. 2.66GB(uncompressed).
* Description of data set
: The aim of this project is to create a solution for this problem and provides
a historic dataset of previous insurance claims. The Claimed amount can be
zero or greater than zero and it is given in US dollars.
* More info. : ​https://www.kaggle.com/c/ClaimPredictonChallenge

## Aims
**1. Searching for exotic particles in high-energy physics**

A. Use pipelines and cross-validation to find the best configuration of parameters and their accuracy. Use a sensible grid for the parameters (for example, three options for each parameter). Use the same splits of training and test data when comparing performances between the algorithms. ​For finding the best configuration of parameters, use 25% of the data chosen randomly from the whole set​.

B. Once finding the best parameter configurations for each algorithm in the smaller subset of the data, use the full dataset to compare the performance of the three algorithms in the cluster. Once again, use the same splits of training and test data when comparing performances between the algorithms. Provide training times when using 10 CORES and 20 CORES. ​Remember to use the batch mode to work on this​.

C. Report the three most relevant features for classification or regression for each method obtained in step B.


