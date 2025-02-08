# DNA Analysis with Next-Generation Sequencing (NGS)

## Overview
This project explores **DNA classification** using **Next-Generation Sequencing (NGS)** techniques. We process **100 DNA sequences**, each containing **57 nucleotides**, to classify them into **promoters (+) and non-promoters (-)** using various **machine learning algorithms**.

## Features
- **Data Preprocessing**: Import, clean, and convert DNA sequences into numerical format.
- **Exploratory Data Analysis (EDA)**: Visualizing class distributions and feature counts.
- **Machine Learning Models**: Training multiple classifiers (KNN, Decision Trees, Random Forest, SVM, Neural Networks, etc.).
- **Model Evaluation**: Comparing accuracy scores and classification reports.

## Installation
Clone the repository and install dependencies:
```sh
$ git clone <repo-url>
$ cd <repo-folder>
$ pip install -r requirements.txt  # Install necessary libraries
```

## Usage
Run the main script to train and evaluate models:
```sh
$ python dna_classifier.py
```

## Dependencies
- Python 3.x
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn

## Results
Each classifier is evaluated based on accuracy using **10-fold cross-validation**. The best-performing model is selected based on classification reports.

