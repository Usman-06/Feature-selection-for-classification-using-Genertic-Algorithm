**Feature Selection for Classification using Genetic Algorithm**

This repository contains code for automatic feature selection in classification tasks using Genetic Algorithm (GA). The code is applied to the Machinery Fault Dataset, which can be downloaded from Kaggle. The GA-based approach optimizes feature subsets, aiming to minimize misclassification rates while considering feature selection costs.

Prerequisites

Python 3.x

Pandas

Scikit-learn



**Getting Started**
Clone this repository to your local machine.
Download the Machinery Fault Dataset from Kaggle and place the CSV files in a folder.
Update the dataset_path variable in the code to point to the folder containing the dataset.
Run the main() function to perform feature selection using GA.
**Genetic Algorithm Functions**
The genetic_algorithm.py file contains essential GA functions, including population generation, fitness evaluation, evolution, and more.

**Results**
The fittest_results() function evaluates the best feature subset obtained from GA runs on both training and test data. The code provides insights into classification accuracy, misclassification rates, and feature selection costs.

**Customize for Your Dataset**

You can adapt this code to your dataset by modifying the fitness function and dataset loading process in the load_data() function.
Enjoy the power of automated feature selection with Genetic Algorithm and optimize your classification models for better performance and interpretability!
