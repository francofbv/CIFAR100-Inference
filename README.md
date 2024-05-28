# REU Assignment 1: CIFAR100 inference

## Model Description
- 8 layer Convolutional Neural Network
- 3 Convolutional layers
  - All 3 layers used a 3x3 kernel with a padding of 1 and the ReLU activation function
- 4 Fully connected layers
  - After flattening, the network uses 4 fully connnected layers
    - fc1: 2048 to 512
    - fc2: 512 to 256
    - fc3: 256 to 128
    - fc4: 128 to 100
   
## Training
- Loss function: CrossEntropyLoss
- Optimizer: Stochastic Gradient Descent
- Batch Size: 64
- Epochs: 

## Results

### Training & Validation
- The following plots show the validation loss and accuracy over 20 epochs:
- ![image](https://github.com/francofbv/CIFAR100-Inference/assets/116112994/5bc548e2-71b4-407d-a974-621c59472fd6)


