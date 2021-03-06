# IART-FEUP - Neural network to rate facial expressions.

#### [Live App](https://iart.herokuapp.com/)

## Contributors

1. [Maria João Mira Paulo](https://github.com/MariaJoaoMiraPaulo)
2. [Nuno Miguel Mendes Ramos](https://github.com/NunoRamos)
3. [Pedro Duarte da Costa](https://github.com/pedro-c)


## Index

1. [Introduction](#intruction)
2. [Resources](#resources)
3. [Project Structure](#project-structure)

## Introduction

In this project, we are going to implement a neural network for recognizing Grammatical Facial Expressions (GFEs) used in the Brazilian Sign Language.
To do so we'll use ConvNetJS, a Javascript library, to train a neural network using backpropagation algorithms. 

#### [Live App](https://iart.herokuapp.com/)

#### [Final Report](https://github.com/pedro-c/IART-FEUP/blob/master/Reports/IART1617_FINAL_GE5_4.pdf)

## Resources
  - [Grammatical Facial Expressions Data Set](http://archive.ics.uci.edu/ml/datasets/Grammatical+Facial+Expressions)
  - [Relevant Paper](http://www.aaai.org/ocs/index.php/FLAIRS/FLAIRS14/paper/viewFile/7788/7821)
  - [ConvNetJS - Javascript library for training Neural Networks](http://cs.stanford.edu/people/karpathy/convnetjs/index.html)
  - [Notes of the Stanford CS class CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/)

## Project Structure

### [GFE Data](https://github.com/pedro-c/IART-FEUP/tree/master/GFE%20Data)

#### Pre-processed

JSON formated pre-processed data can be found in the folder JSON inside each experiment.

![Processed points](https://github.com/pedro-c/IART-FEUP/blob/master/GFEData/Pre-processed/v2.jpg)

#### Raw
Grammatical Facial Expressions for Brazilian Sign Language

The dataset is organized in 36 files: 18 datapoint files and 18 target files, one pair for each video which compose the dataset.The name of the file refers to each video: the letter corresponding to the user (A and B), name of grammatical facial expression and a specification (target or datapoints).

Contains:
  - Datapoints files (* _ datapoints.txt): a timestamp (double) and 100 numeric attributes (double)

  - Targets files (* _ targets.txt): a class attribute (interger)

### [Parser](https://github.com/pedro-c/IART-FEUP/tree/master/Parser)
  Small CLI python program to parse datapoints in a `.txt` files to usefull data in `.json` format

### [Reports](https://github.com/pedro-c/IART-FEUP/tree/master/Repors)
  Project reports.

### [Experiment1: Default experiment](https://github.com/pedro-c/IART-FEUP/tree/master/experiment1)

### [Experiment2: Increased number of datapoints](https://github.com/pedro-c/IART-FEUP/tree/master/experiment1)

### [Experiment3: Reducted number of given neutral expressions](https://github.com/pedro-c/IART-FEUP/tree/master/experiment2)

### [Experiment4: Tested a neural expression for each expression](https://github.com/pedro-c/IART-FEUP/tree/master/experiment3)

### WebApp Screenshot

![App Screenshot](https://github.com/pedro-c/IART-FEUP/blob/master/app-screenshot.png)

