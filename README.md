### PC Baseline

## Vanilla version of PC (MLP) - an ANN with modularity. 
Corresponding to http://ieeexplore.ieee.org/abstract/document/7377956/

## Features:
  - Strictly based on MLP and the code from http://deeplearning.net/.
  - Circuits are equally divided.
  - Outside dropout rate and sparsity coefficient, other circuit descriptions are similar
  - Weight/Learning rate decay is not included

## Main files:
  - execute.py      : experiment configuration for mass execution
  - model.py        : PC definition
  - layer.py        : layer defintion
