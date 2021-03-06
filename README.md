# TV-script-generation

## Table of Contents

1. [Project Overview](#project_overview)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Overview <a name="project_overview"></a>

In this project, I generated Seinfeld TV scripts using RNNs based on part of the [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) of scripts from 9 seasons. The LSTM RNN model will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

## Installation <a name="installation"></a>

1. Python versions 3.6
2. Library and packages: pytorch, os, glob, numpy, pandas, Counter, pickle

## File Descriptions <a name="files"></a>

### Folders: 
**Data:** contains the original data file: <a href="/data/Seinfeld_Scripts.txt">Seinfeld_Scripts</a>

### Files:
**dlnd_tv_script_generation.ipynb:** the main notebook for the TV script generation

**dlnd_tv_script_generation.html:** html format of dlnd_tv_script_generation.ipynb

**helper.py:** contains functions used the main notebook

**preprocess.p:** precleaned dataset (Punctuation tokenized, Words to ints using Bag of Words)

**problem_unittests.py:** contains unit test functions used the main notebook

**trained_rnn.py:** the saved trained rnn model for script generation

**generated_script_1.txt:** generated sample script 1

**generated_script_2.txt:** generated sample script 2

## Results<a name="results"></a>

Using the LSTM RNN model with 2 hidden layer, 300 embeddings and 0.001 learning rate, the final training loss is 3.35 after traing 10 epochs. Two of the sample scripts generated using the model can be found <a href="/generated_script_1.txt">sample #1</a> and <a href="/generated_script_2.txt">sample #2</a>. 

## Licensing, Authors, and Acknowledgements<a name="licensing"></a>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Acknowledge to [Udacity](https://www.udacity.com/) for providing the stater code.  





