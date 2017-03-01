# MoRS-Scores
This repo serves to present MoRS scores in the SemEval Task 3 of 2016

# Official score (MAP for SYS): 0.8115

# Classification results

Acc = 0.7434

P   = 0.7437

R   = 0.9994

F1  = 0.8528


# Detailed ranking results

IR  -- Score for the output of the IR system (baseline).
SYS -- Score for the output of the tested system.

 | IR | SYS
------------ | -------------| ------------ | 
MAP    | 1.0000 | 0.8115
AvgRec | 1.0000 | 0.8142
MRR    | 100.00 | 88.44

 | IR | SYS  | IR | SYS | IR | SYS | IR | SYS
------------ | -------------| ------------ | ------------ | -------------| ------------ | ------------ | -------------| ------------ | ------------ | -------------| ------------ | 
REC-1@01 | 100.00 | 79.10 | ACC@01 | 100.00 | 79.10 | AC1@01 | 1.00 | 0.79 | AC2@01 | 244 | 193
REC-1@02 | 100.00 | 93.85 | ACC@02 | 100.00 | 77.87  AC1@02 | 1.00 | 0.78 | AC2@02 | 488  380
REC-1@03 | 100.00 | 99.18 | ACC@03 | 100.00 | 77.46  AC1@03 | 1.00 | 0.77 | AC2@03 | 732  567
REC-1@04 | 100.00 | 99.59 | ACC@04 | 99.90 | 76.23  AC1@04 | 1.00 | 0.76 | AC2@04 | 975  744
REC-1@05 | 100.00 | 100.00 | ACC@05 | 99.59 | 74.92  AC1@05 | 1.00 | 0.75 | AC2@05 | 1215  914
REC-1@06 | 100.00 | 100.00 | ACC@06 | 98.50 | 74.59  AC1@06 | 1.00 | 0.76 | AC2@06 | 1442 1092
REC-1@07 | 100.00 | 100.00 | ACC@07 | 95.02 | 74.53  AC1@07 | 1.00 | 0.78 | AC2@07 | 1623 1273
REC-1@08 | 100.00 | 100.00 | ACC@08 | 89.55 | 74.49  AC1@08 | 1.00 | 0.83 | AC2@08 | 1748 1454
REC-1@09 | 100.00 | 100.00 | ACC@09 | 81.97 | 74.50  AC1@09 | 1.00 | 0.91 | AC2@09 | 1800 1636
REC-1@10 | 100.00 | 100.00 | ACC@10 | 74.39 | 74.39  AC1@10 | 1.00 | 1.00 | AC2@10 | 1815 1815

REC-1 - percentage of questions with at least 1 correct answer in the top @X positions (useful for tasks where questions have at most one correct answer)

ACC   - accuracy, i.e., number of correct answers retrieved at rank @X normalized by the rank and the total number of questions

AC1   - the number of correct answers at @X normalized by the number of maximum possible answers (perfect re-ranker)

AC2   - the absolute number of correct answers at @X

