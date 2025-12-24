# Graph Neural Network for Fraud Detection

## Overview
This project implements a Graph Neural Network (GNN) to detect fraudulent financial transactions. Users, accounts, and transactions are modeled as nodes in a graph, and their relationships are captured using edges. The model learns transaction behavior patterns using graph structure to classify fraudulent transactions.

## Technologies Used
- Python
- PyTorch
- PyTorch Geometric
- NetworkX
- Google Colab

## Graph Construction
- Nodes: Users, Accounts, Transactions
- Edges:
  - User → Account
  - Account → Transaction

## Model Architecture
- Graph Convolutional Network (GCN)
- Two graph convolution layers
- ReLU activation
- Node-level classification for fraud detection

## Training and Evaluation
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Evaluation Metrics:
  - Precision
  - Recall
  - ROC-AUC

## How to Run
1. Open the notebook in Google Colab
2. Install required dependencies
3. Run all cells sequentially
4. Observe training and evaluation results

## Results
The GNN model successfully learns transaction patterns and detects fraudulent transactions using relational graph information.

## Author
Addepalli Somanadha Sai
