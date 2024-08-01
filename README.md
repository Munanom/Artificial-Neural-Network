# Artificial-Neural-Network

## Overview

This repository contains an assignment that explores the effects of increasing and decreasing the number of layers in an artificial neural network. The neural network is trained to classify species in the Iris dataset using different configurations of layers and neurons. The primary goal is to observe how the changes in the network's architecture affect its performance.

## Contents

- `assignment.Rmd`: The R Markdown document containing the code and analysis for the assignment.
- `README.md`: This README file providing an overview of the project.

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
