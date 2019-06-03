# Text tagging

## Introduction

This project reviews the standard methods in text tagging and experiments extending the approach proposed in [Universal Language Model Fine-tuning for Text Classification (ULMFiT)](https://arxiv.org/abs/1801.06146) while integrating the modifications in a local copy of the [FastAI](https://github.com/fastai/fastai) library. 

## Index
The files/folder contained in this repo are:

- [X] `fastai/ directory`: Contains the modified verion `1.0.31` of the fastai library to inlcude text tagging.
- [X] `ULMFiT_approach`: A notebook with an execution of the Labeler (on working results) and some of the functions integrated in the library.
- [X] `Data_preprocessing_visualization_new.ipynb`: A notebook with Data preprocessing, visualization for the presentation
- [X] `final_project_checkin_template.ipynb`: first machine learning model fitting
- [X] `baseline_optimization.ipynb`: A notebook with grid search and pipeline to tune the machine learning algorithms

The extension of the approach proposed in ULMiT to this task is still an ongoing project. While a working version has been constructed the models results still need to be improved.

## Major issues

While developing the application of ULMFit to text tagging we realized a major issue of using pre-defined models for that task. This is, the tokenization of the up-stream task, which generally is used for several down-stream tasks,  needs to match the one that was provided in the down-stream taks for the text to match the labels.

## Authors

Miguel Romero, Louise Lai, Jenny Kong.
