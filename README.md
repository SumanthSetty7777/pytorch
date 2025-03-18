# pytorch
pytorch basics

PyTorch is a Python-based scientific computing package serving two broad purposes:
    A replacement for NumPy to use the power of GPUs and other accelerators.
    An automatic differentiation library that is useful to implement neural networks.

# Neural networks
Neural networks (NNs) are a collection of nested functions that are executed on some input data. These functions are defined by parameters (consisting of weights and biases), which in PyTorch are stored in tensors.

Training a NN happens in two steps:

# Forward Propagation: 
In forward prop, the NN makes its best guess about the correct output. It runs the input data through each of its functions to make this guess.

# Backward Propagation: 
In backprop, the NN adjusts its parameters proportionate to the error in its guess. It does this by traversing backwards from the output, collecting the derivatives of the error with respect to the parameters of the functions (gradients), and optimizing the parameters using gradient descent. For a more detailed walkthrough of backprop, check out this video from 3Blue1Brown(https://www.youtube.com/watch?v=tIeHLnjs5U8).