I've built and trained two CNNs from scratch using TF sequential for 10 epochs each and compared their prediction accuracies.

Dataset: Fashion MNIST - https://github.com/zalandoresearch/fashion-mnist/tree/master/data/fashion

# **Preprocessing**:
- Normalizing pixel values
- Quadratic intensity scaling
- Image augmentation using imgaug

# **Model 1**:
2 convolutional layers, 2 pooling layers, 1 fully connected layer with ReLU activation and 1 output layer with softmax activation

# **Model 2**:
Same as Model 1, with batch normalization and droput layers added

![alt text](image.png)