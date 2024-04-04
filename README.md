# basic_neural_networks
This repository, is for demonstrating how various libraries can be used for building neural networks.

## Files and their contents
1. neural_nw_with_numpy.ipynb
 - This file contains the demonstration of how a 3-layer neural network can be made from scratch using nothing but numpy, for a non-linear regression problem.
2. neural_network_with_pytorch.ipynb
 - This file contains the demonstration of different ways neural networks can be made for a non linear regression problem using Pytorch. Below are the list of demonstrations.
   - From Scratch without using much of the functionalities provided by PyTorch
   - Layers and model from scratch but using the auto differential features provided by PyTorch
   - By using optimizers and making the layer's class inherit the nn.Module in the implementation
   - Using PyTorch's Builtin functionalities such as optimizers, layers and the Sequential API
   - Using PyTorch's Builtin functionalities such as optimizers, layers and without the Sequential API
3. neural_network_with_pytorch_lightening.ipynb
 - This file contains the demonstration of how you can use PyTorch Lightening and PyTorch to build a neural network. By making your model class inherit the PytorchLightening module and using the layer functionality provided by PyTorch
4. neural_networks_using_tf.ipynb
   - The file contains the following different ways of building a neural network using TensorFlow.
     - From scratch without using any features provided by Tensorflow
     - From scratch but using gradient tape for assisting in backpropogation  (Low level API)
     - Using Optimiers and Subclassing i.e making out model and layer class inherit tf.Module (Low level API)
     - Using built-in layers provided by TensorFlow
     - Using TensorFlow's functional API
     - Using TensorFlow's Sequential API
     - Using Sequential API to build a model for Image classification on MNIST digits dataset
5. neural_nw_using_jax.ipynb
 - The file contains the following different ways of building a neural network using JAX.
    - Everything from scratch
    - Using low level API such as jax.grad to assist in backpropagation , and weight updation
    - Using high level API by implementing the Flax.linen.nn and jax.jit decorators
  
## Video Link:
https://youtu.be/C9n1j7XkXB4
