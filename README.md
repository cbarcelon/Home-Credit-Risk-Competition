# Home-Credit-Default-Risk-Competition

A repository of my files for Home Credit Default Risk Kaggle competition.

This repository is still under work and and a full project report will be uploaded soon.

Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

## Problem Statement

The problem is to build a model that will predict the likelyhood that a loan applicant will default on their loan.

## Metrics

The model will be scoreed area under the ROC curve between the predicted probability and the observed target.

## Data

The dataset in contained in 7 seperate csv files.  It consists of 307511 labeled loan applications to train a model with and 48000 applications to be used as the test set.
The sepearate csv files all contain different data that may contribute to a loan applicants credit worthiness.  The files need to be combined and new features engineered in order to create a strong predictive model.

## Algorithms

The main algorithm currently in use is LightGBM, a fast, distributed, high performance gradient boosting (GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, used for ranking, classification and many other machine learning tasks. It is under the umbrella of the DMTK(http://github.com/microsoft/dmtk) project of Microsoft.
