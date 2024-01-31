# GNN Profiling with PyTorch and PyTorch Geometric

## Introduction
This repository contains a Graph Neural Network (GNN) implemented using PyTorch Geometric. The GNN is trained on the Cora dataset, and profiling is performed to analyze the execution time of the training process.

## Authors
- Kavya Shridhar Lolla (S20210010117)
- Jai Sri Aishwarya (S20210010070)

## Dependencies
Ensure you have the following dependencies installed:
- PyTorch
- PyTorch Geometric
- torch-geometric
- line_profiler

You can install these dependencies using the following command:

pip install torch torch-geometric line_profiler

##Steps to profile the GNN training
1.Clone the Repository
 git clone https://github.com/shernoble/HPC_Assignment1.git
 cd HPC_Assignment1
2.install dependencies
3.open the code as jupyter notebook and run the code
4. Open the profile_output.txt file to analyze the cumulative time taken by different functions during the training.  

The line that initiates profiling of code:
%prun -s cumulative -T profile_output.txt train_larger_model(larger_model, data, optimizer, criterion)

