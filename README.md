# Project Description

## 102217161 TOPSIS PACKAGE Arshiya Jain

*Roll Number:* 102217161  
*Subgroup:* 3Q25  

The program takes a CSV file containing our data to be ranked, weights and impacts in the form of "+" or "-", separated by commas as inputs and then outputs a resultant CSV file with two additional columns of performance score and ranks.

---

## What is TOPSIS?

TOPSIS, Technique of Order Preference Similarity to the Ideal Solution, is a multi-criteria decision analysis method (MCDM).  
It chooses the alternative of the shortest Euclidean distance from the ideal solution and the greatest distance from the negative ideal solution.

---

## Installation

### How to install the TOPSIS package

Using pip install:
```bash
pip install 102217053-topsis


The output will then be saved in a newly created CSV file whose name will be provided in the command line by the user.

## Input File [data.csv]:
Topsis mathematical operations to be performed on the input file which contains a dataset having different fields.

## Weights ["0.2,0.2,0.2,0.2,0.2"]:
The weights assigned to the different parameters in the dataset should be passed in the argument, separated by commas.

## Impacts ["+,+,-,+,-"]:
The impacts are passed to consider which parameters have a positive impact on the decision and which ones have a negative impact. Only + and - values should be passed and should be separated with , only.

## Output File [output.csv]:
This argument is used to pass the path of the result file where we want the rank and performance score to be stored.