# rldm-project-3
CS7642 Project 3 Source, summer 2017 - Replicating multi-agent soccer game experiment by Zhi Chen (ID: zchen482)

Github Source Code: https://github.gatech.edu/zchen482/rldm-project-3

#### author: zchen482
#### date: 7/23/2017

### Environment
requires: python 3.6; numpy 1.13; cvxopt 1.1.9

### Result Output
results are stored in .txt in folder "./result/".

### Report Data Example
Example of data used for report is stored in "./result/report_data/".

### Instructions
1. To reproduce Correlated-Q experiment, run CEQ.py (make sure runCEQ() is uncommented at main). This generates .txt result file named "CEQ_[timestamp]". 

2. To reproduce Friend-Q experiment, run FQ.py. This generates .txt result file named "FQ_[timestamp]". 

3. To reproduce Foe-Q experiment, run FoeQ.py (make sure runFoeQ() is uncommented at main). This generates .txt result file named "FoeQ_[timestamp]". 

4. To reproduce QLearner experiment, run QL.py. This generates .txt result file named "QL_[timestamp]". 
