## Overview

This Python script provides a solution to the Traveling Thief Problem (TTP) using a genetic algorithm approach. The script reads data from various TTP datasets, performs genetic algorithm operations such as crossover and mutation, and evaluates the fitness of the solutions based on both profit and time.
This Python script is divided into four parts:
   1. Fundalmental functions of EA for TTP
   2. Main GA function- Rank selection, Crossover, Replace Weakest
   3. Experiments: Adjust the parameters & draw plots of results
   4. Validation-function of Result for different algorithms

## Environment Setup

Run the following line in your environment:

    pip install -r requirements.txt

## Directory Setup
The directory should include the following files.

        ├── NIC_Group_GA.ipynb #Jupyter Notebook
        ├── a280-n1395.txt   
        ├── a280-n279.txt
        ├── a280-n2790.txt
        ├── fnl4461-n22300.txt
        ├── fnl4461-n4460.txt
        ├── fnl4461-n44600.txt
        ├── pla33810-n169045.txt
        ├── pla33810-n33809.txt
        ├── pla33810-n338090.txt                 
        ├── requirements.txt #Dependencies to be installed
        └── README.md
        
## Configuration
The script offers a range of configuration options to customize the behavior of the genetic algorithm. Adjust parameters such as population size, generations, and mutation rate to fine-tune the genetic algorithm for your specific requirements.

In the part of 'Experiments: Adjust the parameters & draw plots of results',we can
modify these parameters for different experiments.

    1. Adjust the parameters in the GetBasicData(file_path) function to select different datasets
    2. parameters:
         seed = 2000
         popSize = 50
         iterations = 10000
         file_path=0

## How to run
Choose the 'Restart & Run All' option in Kernel Tab of the Jupyter Notebook