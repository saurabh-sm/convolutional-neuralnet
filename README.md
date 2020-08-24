# Convolutional Neural Network

Convolutional neural networks are computationally more intensive (in terms of minutes per epoch) than multi-layer perceptrons, which makes the presence of a GPU or TPU even more important. 

This project uses the EMNIST letters dataset which is built into [Tensorflow]. A validation set is also used as lots of hyperparameters are tuned, and also because it is a good practice. The test set is used only for the final evaluation of the trained and tuned network.

# A CNN for EMNIST Letters

This project builds upon [MLP for EMNIST Letters] where alternative architectures are explored, and more hyperparameters and optimizers are tuned. The training process is visualized by plotting a loss curve using [TensorBoard].


[Tensorflow]: https://www.tensorflow.org/
[MLP for EMNIST Letters]: https://github.com/saurami/Multi-Layer-Perceptron
[TensorBoard]: https://www.tensorflow.org/tensorboard/get_started 
