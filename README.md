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
- Epochs: 20

## Results

### Training & Validation
- The following plots show the validation loss and accuracy over 20 epochs:
- ![image](https://github.com/francofbv/CIFAR100-Inference/assets/116112994/5bc548e2-71b4-407d-a974-621c59472fd6)
- The model achievs 42% accuracy on the dev set, which is quite good considering the size of the model

#### Samples
- Below are a few samples of the model's predictions and the ground truth class from the test set
![Example 1:](https://github.com/francofbv/CIFAR100-Inference/assets/116112994/c39e2b93-d0ed-4d68-b1cb-292e94f39cb2) - predicted: 'Dinosoar', True: 'Elephant'
![Example 2:](https://github.com/francofbv/CIFAR100-Inference/assets/116112994/946a8d87-0bc7-4ead-9705-a138048e2c77) - predicted: 'Wolf', True: 'Television'
![Example 3:](https://github.com/francofbv/CIFAR100-Inference/assets/116112994/9a794815-250b-49f9-a28c-9ee0776a7b91) - predicted: 'Skyscraper', True: 'Skyscraper'





