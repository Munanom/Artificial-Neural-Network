# Artificial-Neural-Network

## Overview

This repository contains an assignment that explores the effects of increasing and decreasing the number of layers in an artificial neural network. The neural network is trained to classify species in the Iris dataset using different configurations of layers and neurons. The primary goal is to observe how the changes in the network's architecture affect its performance.

## Contents

- `assignment.Rmd`: The R Markdown document containing the code and analysis for the assignment.
- `README.md`: This README file providing an overview of the project.

Project Overview
The assignment involves the following tasks:

## Data Preparation:

Load the Iris dataset and preprocess it by converting character variables to factors.
Split the dataset into training and testing sets.
Model Training and Evaluation:

Train multiple neural network models with different architectures using the neuralnet package.
Evaluate model performance by predicting species on the test set and calculating accuracy.
Configurations Tested:

Model 1: Neural network with hidden layers [30, 18, 14, 12, 12, 6]
Model 2: Neural network with hidden layers [30, 24, 20, 18, 16, 14, 12, 8, 6, 3]
Model 3: Neural network with hidden layers [3, 12]
Results:

Each model's accuracy is evaluated and compared.
Plots of the neural network architecture and performance metrics are included.
## Files Included
R Markdown Document (.Rmd): Contains the code for data preparation, model training, and evaluation.
Output Document (.pdf): Compiled PDF report with results and plots.
Installation and Usage
To run the code, make sure to install the necessary R packages:

## Requirements

- R (version 4.0.0 or later)
- R packages:
  - `neuralnet`
  - `keras`
  - `tensorflow`
  - `tidyverse`

## Installation

1. **Install R**: If you don't have R installed, download and install it from [CRAN](https://cran.r-project.org/).

2. **Install Required Packages**: Open R and run the following command to install the necessary packages:
   ```R
   install.packages(c('neuralnet', 'keras', 'tensorflow', 'tidyverse'), dependencies = TRUE)

## License
This project is licensed under the MIT License - see the LICENSE file for details.
