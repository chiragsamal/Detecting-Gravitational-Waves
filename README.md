# Detecting-Gravitational-Waves
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

Tutorial for detecting gravitational waves: A beginner's guide
<img width="742" height="480" src="https://github.com/chiragsamal/Detecting-Gravitational-Waves/blob/main/images/planets.jpg" />


## Overview

This repository contains code for detecting long-lasting gravitational wave signals using Short-Time Fourier Transforms (SFTs) data from two gravitational-wave interferometers (LIGO Hanford and LIGO Livingston). The goal is to build a model that is sensitive enough to distinguish between noisy data and weak but persistent signals emitted by rapidly rotating neutron stars. 

The repository includes an Exploratory Data Analysis, data augmentation techniques, and a baseline model using EfficientNet B3 to detect gravitational-wave signals.

### Dataset

The G2Net Detecting Continuous Gravitational Wave competition dataset is used in this project, and can be downloaded from [Kaggle](https://www.kaggle.com/competitions/g2net-detecting-continuous-gravitational-waves/data).

### Requirements

To install the required packages, you can run the following command:

`pip install -r requirements.txt`

### Sections

This repository is divided into the following sections:

- Exploratory Data Analysis
- Data Augmentation
- Baseline Model

## How to Use

To use this repository, you can clone it using git:

`git clone https://github.com/chiragsamal/Detecting-Gravitational-Waves.git`


You can then run the code in each section using Jupyter notebooks.

## References
 - [[G2Net] Understand the Data](https://www.kaggle.com/code/siddhantsingh1/g2net-understand-the-data)
 - [G2Net: EDA That Gives You insights](https://www.kaggle.com/code/siddhantsingh1/g2net-eda-that-gives-you-insights)
 - [G2Net Getting Started + EDA ](https://www.kaggle.com/code/edwardcrookenden/g2net-getting-started-eda)
 - [G2Net: Data and Augmentation](https://www.kaggle.com/code/maharshipandya/g2net-data-and-augmentation)
 - [G2Net Basic Audio Data Augmentation](https://www.kaggle.com/code/myso1987/g2net-basic-audio-data-augmentation)
 - [G2Net TF Baseline 360](https://www.kaggle.com/code/crischir/g2net-tf-baseline-360)
 - [Basic Spectrogram image classification](https://www.kaggle.com/code/junkoda/basic-spectrogram-image-classification)
 - [G2Net TF Keras train test with TPU](https://www.kaggle.com/code/itsuki9180/g2net-tf-keras-train-test-with-tpu)
 - [G2Net - Record Generation](https://www.kaggle.com/code/morodertobias/g2net-record-generation)
 

