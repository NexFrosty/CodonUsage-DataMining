# Codon Usage Analysis Using Data Mining Techniques

## Overview

The project focuses on analyzing codon usage patterns to gain insights into the genetic characteristics of organisms. By applying various machine learning models, we aim to predict key genomic and evolutionary traits using codon frequencies.

## Data Source

The data used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php), specifically the Codon Usage dataset. It includes 23 numeric attributes and 3 nominal attributes across 10,257 instances.

## Project Structure

- `Data Acquisition`: Process of collecting and understanding the dataset's attributes.
- `Data Preparation`: Steps include data cleaning, transformation (normalization and discretization), and reduction to ensure data quality before analysis.
- `Model Development and Evaluation`: Application of machine learning models like k-Nearest Neighbors, Random Forest, Support Vector Machines, and J48 to evaluate their performance in predicting the DNA type based on codon usage.
- `Results`: Comparison of model performances and their effectiveness in classifying codon usage patterns.

## Key Findings

- Codon usage bias levels can predict genomic and evolutionary features of organisms.
- Machine learning models, specifically SVM, RF, and kNN, showed high accuracy in predicting DNA type and taxonomic identity from codon frequencies.
- The analysis highlights the potential applications of codon usage patterns in identifying evolutionary origins and genetic compositions of organisms.

## Tools Used

- **WEKA**: For data cleaning, preprocessing, and machine learning model implementation.
- **Microsoft Excel**: Used for the initial data cleaning and preparation steps.

## References

- Hallee, L., & Khomtchouk, B. B. (2023). Machine learning classifiers predict key genomic and evolutionary traits across the kingdoms of life. Scientific Reports, 13(1). https://doi.org/10.1038/s41598-023-28965-7
