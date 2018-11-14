# Navigation Project Report

## Learning Algorithim

For this project, I implemented a Deep Q-Network (DQN) to solve the problem of deciding which of the available actions to
take for any given state. I used a network architecture consisting of 2 fully connected layers, each with 64 nodes.
For training, I used an Adam Optimizer with a learning rate of 5e-4. The gamma value (discount factor) for future rewards
was 0.99, and epsilon (probability of uniformly chosen action) started at 1.00 and eventually decayed to 0.01 .

## Plot of Rewards during training and evaluation
