
# Neurograd
This is a small autograd engine, made purely from numpy and python.Implements backpropagation (reverse-mode autodiff) over a dynamically built **Directed Acyclic Graph** where each node in the DAG is a scalar value, and edges represent operations like addition or multiplication .This structure allows the engine to correctly compute gradients by traversing the graph in reverse order. Also a small neural networks library on top of it with a PyTorch-like API.


