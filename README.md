# Minimal Model Reasoning with Machine Learning Models
This repository uses the pre-trained models and code from https://github.com/porscheofficial/sls_sat_solving_with_deep_learning/blob/main/python/src/evaluate_with_given_params.py.

Modifications to the code have been made and it has been adapted to use the Deep Learning SLS Sat Solving Model for Minimal Model Solving.

Deep Learning Model:
Input: A CNF File (solution file is automatically generated)
Output: SAT or UNSAT (either the formula is UNSAT or the model requires more steps to solve)

Main Function
Input: CNF File(s)
Output: A Minimal Model for each CNF Formula