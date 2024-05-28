# REU Assignment 1: CIFAR100 inference

## Model Description
- 8 layer Convolutional Neural Network
- 3 Convolutional layers
  - All 3 layers used a 3x3 kernel with a padding of 1 and the ReLU activation function
- 4 Fully connected layers
  - After flattening, the network uses 4 fully connnected layers
    - fc1: 2048 $\Righarrow$ 512
    - fc2: 512 $\Righarrow$ 256
    - fc3: 256 $\Righarrow$ 128
    - fc4: 128 $\Righarrow$ 100

## Model Performance
- 42% accuracy on CIFAR100 dev set on 20 epochs

