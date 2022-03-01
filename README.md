# Machine-Learning-Approach-Towards-Predicting-Query-Response-Time

Follow the instructions in this file to execute the code. 

1. Import the following modules in your python environment - 
a) numpy
b) sklearn
c) torch

2. Choose the .train file that you want to run. 

3. Open QueryTimePredictionCode.ipynb. 

4. Depending on the .train file that you have selected, fill the second cell of the jupyter notebook. Enter the name of the .train file. For "numfeatures" and "test_set" enter the following values depending on the file -
a) HashJoin.train: numfeatures = 10; test_set = 300
b) IndexScan.train: numfeatures = 10; test_set = 400
c) Sort-quicksort.train: numfeatures = 12; test_set = 100
d) Hashing.train: numfeatures = 14; test_set = 200
e) Limit.train: numfeatures = 10; test_set = 300
f) NestedLoopIndexScan.train: numfeatures = 10; test_set = 300
g) SequentialScan.train: numfeatures = 10; test_set = 400

