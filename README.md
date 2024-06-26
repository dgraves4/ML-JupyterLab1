# JupyterLab Machine Learning Project

## Project Overview

This project is a part of the Lab 1 assignment for the Machine Learning course. The goal of this lab is to set up a Python environment with JupyterLab and required frameworks, and to perform a simple guided machine learning application using a dataset. The steps include installing packages, running JupyterLab, exploring the data, training a machine learning model, and evaluating its performance.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Process](#process)
  - [1. Setting Up the Environment](#1-setting-up-the-environment)
  - [2. Exploring the Data](#2-exploring-the-data)
  - [3. Creating and Training the Model](#3-creating-and-training-the-model)
  - [4. Evaluating the Model](#4-evaluating-the-model)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)

## Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Steps

1. Clone the repository to your local machine:

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv .venv
    source .venv/Scripts/activate  # On Windows
    source .venv/bin/activate      # On MacOS/Linux
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start JupyterLab:

    ```bash
    jupyter lab
    ```

2. Open the `lab1_starter.ipynb` notebook.

## Data

The dataset used in this project is `automobile_price_data3.csv`. It contains various features of automobiles, including `make`, `fuel`, `body`, `drive`, `weight`, `engine-size`, `bhp`, `mpg`, and `price`.

## Process

### 1. Setting Up the Environment

- Installed necessary packages: NumPy, Pandas, Matplotlib, scikit-learn, and JupyterLab.
- Created a virtual environment and installed packages using `requirements.txt`.

### 2. Exploring the Data

- Loaded the dataset into a Pandas DataFrame.
- Displayed the first 10 rows of the dataset.
- Generated histograms for numerical features to understand their distributions.
- Identified and handled missing values in the dataset.

### 3. Creating and Training the Model

- Split the dataset into training and test sets using `train_test_split`.
- Trained a Linear Regression model using `scikit-learn`.

### 4. Evaluating the Model

- Displayed the internal parameters of the trained model (intercept and coefficients).
- Made predictions on the test set and calculated the Root Mean Squared Error (RMSE) to evaluate the model's performance.

## Results

- The dataset was successfully split into 157 training samples and 40 test samples.
- The Linear Regression model was trained and evaluated.
- The RMSE value indicates the model's performance on predicting car prices.

## Conclusion

This project demonstrates the basic steps of setting up a Python environment for data science, exploring a dataset, training a machine learning model, and evaluating its performance. The process can be referenced for future projects involving similar tasks.
