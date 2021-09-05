# PyTorch_Basic
# What is CUDA?
we will compile all model/code on google colab, so we will use CUDA capable GPU.

Most people confuse CUDA for a language or maybe an API. It is not. ... CUDA is a parallel computing platform and programming model that makes using a GPU for general purpose computing simple and elegant.

# Set "zero_grad()" in pytorch
In PyTorch , for every mini-batch during the training phase, we need to explicitly set the gradients to zero before starting to do backpropragation (i.e., updation of Weights and biases) because PyTorch accumulates the gradients on subsequent backward passes. This is convenient while training RNNs.
