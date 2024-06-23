# Sentiment Analysis

This repository contains code for performing sentiment analysis on text data. The project includes data loading, preprocessing, feature extraction, model training, and evaluation.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](\usage)
- [Data](#data)
- [Features](#features)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
The goal of this project is to build a sentiment analysis model that can classify text as positive or negative. The model is trained on labeled text data and evaluated on test data to ensure its accuracy.

## Installation
To install the necessary dependencies, run the follwing command:

``bash
pip install -r requirements.txt`b

## Usage
1. Clone the repository:    
```bash
git clone https://github.com/qbk90/sentiment-analysis.git cd sentiment-analysis``
2. Run the main script to perform sentiment analysis:
```python main.py``

## Data
The dataset consists of text reviews labeled as positive or negative. The data files are:
- `reviews_train.tsv`: Training data
- `reviews_val.tsv`: Validation data
- `reviews_test.tsv`: Test data
- `reviews_submit.tsv`: Submission data
- `toy_data.tsv`: Toy dataset for testing


## Features The features are extracted using various techniques including bag-of-words and TF-IDF. The feature extraction process is implemented in the `utils.py`script.

## Models
The models are trained using the main.py script. Different machine learning algorithms Such as logistic regression, Naive Bayes, and SVM can be used for training. The script also includes hyperparameter tuning and model evaluation.

## Results
The performance of the models is evaluated using accuracy, precision, recall, and F1}-score. The results are displayed as plots and printed in the console.

## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIFUTING.md) for more information.


## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
