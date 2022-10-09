# Deep-Learning-Project


In the first mini-project, we implement an image denoiser network using PyTorch. The used network architecture is a convolutional autoencoder that generates image-to-image mappings. The input and the target pairs of the training data are noisy images, and no clean reference is involved in the training process. This model is known as a Noise2Noise network https://arxiv.org/abs/1803.04189


In the second project, we implement the network of the previous project using only Pytorch tensor operations. This frameowork consists of the implementa- tion of the following modules with the associated forward and backward passes:

• 2-dimensional convolution (Conv2d) and 2-dimensional transposed convolution (TransposeConv2d) layers

• Upsampling layers: each (Upsampling) layer is wrapper around the (TransposeConv2d) layer

• ReLU and Sigmoid activation functions

• Sequential module which combines all the modules involved in the framework

• Mean Squared Error (MSE) loss

• Optimization module: Stochastic Gradient Descent(SGD)
