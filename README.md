# CLLearner
This folder contains our implementation of a concept length learner in description logics

## To reproduce the results:
*-* Install OntoPy and all its dependencies

*-* Clone this repository: git clone https://github.com/Jean-KOUAGOU/CLLearner

*-* Choose the knowledge you want in main.py by choosing the right path in the argument parser

*-* If GPU is available, set train_on_gpu to True

*-* In the train-test split line, choose test_size=0.05

*-* Set alpha = 1 or alpha = 0.

*-* Save and run main.py

*-* When prompted for the number of iterations, enter 1000 (if GPU is available)

*-* When prompted for a value for print_every, choose a large value, e.g., 100
