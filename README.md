# CLLearner
This repository contains our implementation (in Python) of a concept length learner in description logics

## To reproduce the results:
*-* Install OntoPy and all its dependencies

*-* Clone this repository: git clone https://github.com/Jean-KOUAGOU/CLLearner

*-* Choose the knowledge you want in main.py by choosing the right path in the argument parser. Not that the family_forte knowledge graph is a small/toy data set, and should not be used here. Please feel free to add another big knowledge graph and new experiments.

*-* If GPU is available, set train_on_gpu to True

*-* In the train-test split line, choose test_size = 0.05

*-* Set alpha = 1 or alpha = 0.

*-* Save and run main.py

*-* When prompted for the number of iterations, enter 1000 (if GPU is available)

*-* When prompted for a value for print_every, input an integer which represents the inverse-frequency at which training details are shown, and controls the smoothness of training curves. 
