# P2P Smart Grid Blockchain Anomaly Detection

This project detects anomalous transactions in a peer-to-peer smart grid blockchain dataset using unsupervised machine learning.

## Overview

The dataset contains simulated blockchain transactions from a P2P energy trading network, where consumers, producers, and a grid operator exchange energy and payments.

Since the dataset has no labeled anomalies, this project uses unsupervised anomaly detection methods.

## Methods Used

* Isolation Forest
* Local Outlier Factor
* One-Class SVM
* Majority-vote ensemble

## Workflow

1. Exploratory data analysis
2. Data preprocessing
3. Feature engineering
4. Model training
5. Ensemble voting
6. Anomaly analysis and visualization

## Features

The project uses transaction, time-based, network, and block-level features such as:

* Transaction amount
* Transaction energy
* Sender and recipient behavior
* Network centrality
* Block size
* Block nonce
* Rolling transaction statistics

## Results

The ensemble model flags transactions as anomalous when at least two models agree. This helps reduce model-specific false positives and gives a more stable anomaly detection result.

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* NetworkX
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Goal

To build a simple and practical anomaly detection pipeline for blockchain-based P2P smart grid transactions without using labeled anomaly data.

