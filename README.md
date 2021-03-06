# Masters-thesis-Industrial-ML-GNN

The code of experiments for the master's thesis: **Industrial ML: graph neural networks for fault diagnosis in multivariate sensor data**.

## Dataset (TEP)

The Tennessee Eastman Process (extended).

## Experiment 1 (Fault Diagnosis)

`Experiment_1.ipynb` - training of proposed GNN model with graph structure learning layer for Fault Diagnosis task.

## Experiment 2 (Quality of obtained adjacency matrices)

`Experiment_2_1.ipynb` - training of GNN model with another architecture without graph structure learning layer. Adjacency matrices were obtained in Experiment 1:

`corr_A.pt` - adjacency matrix obtained by correlation method.

`direct_A.pt` - adjacency matrix obtained during the Experiment 1 for directed graph structure.

`relu_A.pt` - adjacency matrix obtained during the Experiment 1 as matrix of parameters.

`und_A.pt` - adjacency matrix obtained during the Experiment 1 for undirected graph structure.

`uni_A.pt` - adjacency matrix obtained during the Experiment 1 for uni-directed graph structure.

`Experiment_2_2.ipynb` - to compare adjacency matrix with TEP diagram, GNN model from Experiment 1 was trained with max number of edges for each node equal to 3.

## Experiment 3 (Model with several graph structure learning layers)

`Experiment_3.ipynb` - training of novel GNN model with several graph structure learning layers.
