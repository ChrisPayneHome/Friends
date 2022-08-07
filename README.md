# Synthetic Friends Script

![friends](https://user-images.githubusercontent.com/67926222/183304905-dd9c965b-3929-4924-94eb-4a458b5fe94b.jpg)


## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
3. [Markdown](#markdown)
4. [Jupyter Notebook](#notebook)
4. [Model](#model)


## Introduction

A text generation project using data from the tv show Friends to generate a scene using AI, written in Python. Specifically, this project uses an LSTM network trained on cleaned script data from the show.

## Data

This project uses data from a 2020 edition of tidy tuesday that can be found <a href="https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-09-08">here</a>. The folder contains the script data and info data taken from the tidy tuesday project, as well as the cleaned subset of the data that was used to train the model.

## Markdown

The .Rmd and accompanying .html files contain the un-knitted and knitted versions of the Rmarkdown file containing all the R code written for this project. This code was written to identify and visualise the subset of the data used to train the model. Then to actually extract and write this data into the corpus.csv file.

## Notebook

This Jupyter Notebook contains the vast majority of the code written for the project. Within this workbook I import the corpus data mentioned above, clean and prepare it for the model, create and train the model using this data, and generate the scene. 

## Model

The Friends_writer.h5 file is the trained LSTM model used for this project. The model was trained on the aforementioned corpus data for 100 epochs (> 1 day's worth of training time). Rather than re-running the training procedure, it would be best to import this model when attempting to re-run this project.


