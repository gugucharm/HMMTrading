BTC Trading Analysis with HMM

Overview

This repository is a gathering of a few files analyzing / trading the BTC/USD pair with the use of Hidden Markov Models.
Please don't use in in any business application before considering any shortcomings of this code.

Project Structure

The repository contains the following files:

BTC_test.ipynb - Fetches price data, train/test splits it and showcases a chart with the hidden states.

functions.ipynb - Container for necessary functions used in notebooks.

imports.ipynb - Handles installing and then importing libraries.

runner.ipynb - It is a trading bot sending out signals to Pushbullet API whenever a state change occurs. It uses train data, so it is NOT ready to be implemented for real trading

requirements.txt - Lists required dependencies for running the project.

Installation

To set up the environment, clone the repository and install dependencies:

pip install -r requirements.txt

Usage

Open Jupyter Notebook:

jupyter notebook

Run imports.ipynb to load necessary packages and data.

Execute functions.ipynb to define required functions.

Run BTC_test.ipynb to perform Bitcoin trading analysis.

Use runner.ipynb to execute the full workflow.

Requirements

Ensure you have Python installed along with the necessary libraries listed in requirements.txt. The project primarily uses:

hmmlearn

pandas

numpy

matplotlib

yfinance

scikit-learn
