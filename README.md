# GAT-GRU
A spatio-temporal graph neural network for traffic forecasting. Final project for Yale CPSC 483/583: Deep Learning on Graph-Structured Data (Fall 2024).

Traffic forecasting is important to many facets of urban planning, particularly real-time traffic management and routing. Here I propose a novel GAT-GRU
architecture to perform traffic forecasting. The model combines a Graph Attention Network (GAT) with a Gated Recurrent Unit (GRU)
network to learn both spatial and temporal dependencies. Experiments show that the model can outperform multiple state-of-the-art baselines, highlighting the potential of hybrid attention-based graph convolution and recurrent architectures for traffic forecasting.

In the interest of reproducability, the Jupyter notebooks can be found in the `code` directory. The models were trained on Kaggle, so some filepath references may need to be modified.
