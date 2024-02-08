# Credit Card Fraud (Self Organizing Map)

## Self Organizing Maps

Self-Organizing Maps (SOMs), also known as Kohonen maps, are a type of artificial neural network (ANN) used for unsupervised learning and dimensionality reduction.

The main idea behind SOMs is to transform high-dimensional input data into a lower-dimensional space while preserving the topological properties of the input space. This means that similar input data points are mapped to nearby locations in the lower-dimensional map.

1. Initialization

SOMs start by randomly initializing a set of neurons in a grid-like structure. Each neuron has a weight vector that is the same length as the input data.

2. Training

During the training process, the SOM iteratively adjusts its neurons' weights to better represent the input data. At each iteration:

A random input vector is selected.
The neuron whose weight vector is most similar to the input vector (i.e., has the smallest distance in the input space) is identified. This neuron is called the "winning neuron" or "best matching unit" (BMU).
The weights of the winning neuron, as well as its neighboring neurons (according to a predefined neighborhood function), are adjusted to be closer to the input vector. This adjustment process helps the SOM gradually learn the structure of the input data.
Convergence: The training process continues for a specified number of iterations or until convergence criteria are met (e.g., no significant changes in neuron weights). Once training is complete, the SOM forms a low-dimensional map where similar data points are located close to each other, preserving the topological relationships of the input space.

## Output

<p align="center">
  <img src="https://github.com/Neill-Erasmus/credit-card-fraud/raw/main/assets/141222943/f6c16d87-a012-49ff-be7a-87b76b7d75e9" alt="output">
</p>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
