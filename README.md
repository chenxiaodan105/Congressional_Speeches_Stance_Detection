# Contents
[Introduction](#Introduction)

[How to Use](#How-to-Use)

## Introduction

Companies are sensitive to political policies. However, it could bring them a lot of benefits, for example, the fund and support from the government, if they could catch up with political trends beforehand. Stance detection, also known as holding attitudes over things, could be the key to political trends.In this project, NLP method is used to do the prediction based on 2 sessions of congressional bills and transcripts.Just explore it and have fun !

## How to Use
* The data and pretrained GloVe file's size is beyond the GitHub's limit, so you could download them through links below
* Download [Data](https://drive.google.com/open?id=1wChMSMjrJ9Cbb8wzN3hU8X3fxzA_SakT) 
* Download [pretrained GloVe](https://drive.google.com/open?id=1Ez9jDgCfU4Nar2wobzic79UAGFLnzmHF) for word embedding
* Go to code file and explore!

| file |  use | explaination |
| ----------- | ----------- | ----------- | 
| data_preprocessing.py | text preprocessing | tokenization, split data, remove stop words, remove special words and so on |
| relabel_model.py | relabel data using regular expression | relabel speeches by detecting key words |
| DL_Models.ipython | Deep Learning Models | two models |
| DL_Models_with_F1_score.ipython | Deep learning Models with the metric F1 score||
| ML_Models_with_Imbalance_Data_Handling.ipython  | ML Models and Imbalance data Handling| six models |
| data_relabelling_and_wrangling.ipython |EDA|EDA|








