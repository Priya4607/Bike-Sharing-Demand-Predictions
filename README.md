# Bike sharing demand predictions

A demonstration of bike sharing rental predictions using a simple neural network. It is classic regression modelling problem.

This problem may yield better results using other machine learning algorithms, however the intention behind the project is to familiarize onself with the basics of building neural network.

The dataset is from [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

## Table of Contents
<!-- MarkdownTOC autolink="true" bracket="round" autoanchor="false" lowercase="only_ascii" uri_encoding="true" levels="1,2,3,4" -->
- [Setup](#setup)
- [Usage](#usage)
- [Inference](#inference)
- [Acknowledgements](#acknowledgements)
<!-- /MarkdownTOC -->
## Setup
Requires python 3.0+ version.

To install the dependencies,
```
sudo apt-get --no-install-recommends install -y python3-pip
pip install -U pip
```
Clone the project,
```
git clone https://github.com/Priya4607/Bike-Sharing-Demand-Predictions.git
cd Bike-Sharing-Demand-Predictions
pip install -r requirements.txt
```
## Usage
To run the notebook start a local jupyter server from the project folder,
```
jupyter notebook
```

## Inference
As you can see that the predictions are pretty spot-on for most of the days, except during holiday season. Owing to the fact that the data is available for only past two years, the network sees only two such points which doesn't help much in making a good prediction.

## Acknowledgements
This project is a part of my udacity's Deep Learning Specialization Nanodegree.