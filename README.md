# COVID19 Status classification models

This repo contains all the files of the classification model built in order to predict the status of a COVID19 patient. We propose 2 different models trained with INS public domain data on positives cases in Colombia.

For that purpose, the pipeline for training and testing is defined as follows:
- Exploratory data analysis
- Preprocessing
- Training models for prediction
- Model comparison

As a result of the above pipeline, a multi-class Support Vector Machine was selected as the best model for prediction of patient state. This pipeline and the corresponding analysis can be found in the pipeline.ipynb notebook. Some lines have been commented to enhance presentation, due to the length of their output. If you want to check their output, please clone this repo and uncomment all commented lines.


