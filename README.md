# Data-Analysis-on-a-Police-Dataset

This repository contains a Jupyter Notebook that performs various data analysis tasks on a police dataset. The analysis includes data cleaning, exploration, and extracting insights related to police stops.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The Police Data Analysis project focuses on analyzing a dataset containing information about police stops. The primary objectives include cleaning the data, exploring various attributes, and extracting meaningful insights about different violations and the impact of gender on police searches.

## Features

- **Data Loading**: Load the police dataset using Pandas.
- **Data Cleaning**: Identify and handle missing values by dropping columns with only missing values.
- **Data Exploration**: Inspect the dataset, including its shape and columns.
- **Violation Analysis**: Determine who is stopped more often for speeding based on gender.
- **Search Conducted Analysis**: Analyze whether gender affects who gets searched during a stop.
- **Stop Duration Analysis**: Calculate the mean stop duration by mapping stop duration categories to numerical values.
- **Age Distribution Analysis**: Compare age distributions for each violation type using groupby and descriptive statistics.

## Installation

To run the notebook and perform the analysis, you'll need to have Python and Jupyter Notebook installed on your system. Additionally, you'll need to install the required Python libraries.

1. Clone this repository:
    ```bash
    git clone https://github.com/Soniya-krishikka/Data-Analysis-on-a-Police-Dataset.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Data-Analysis-on-a-Police-Dataset
    ```
3. Install the required libraries:
    ```bash
    pip install pandas
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. In the Jupyter Notebook interface, navigate to the project directory and open `Project 3 - Police Data analysis.ipynb`.
3. Run the cells in the notebook to perform the data analysis.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create a pull request or open an issue.

