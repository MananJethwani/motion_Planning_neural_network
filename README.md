# Motion Planning Neural Network

### About

This repo implements motion planning using neural networks and reinforcement learning.

The basic approach is to use the Q-learning approach which comes under reinforcement learning.

We used a neural network with 2 layers consisting of 2 input nodes and 4 output nodes, output nodes have 4 values for the 4 actions. Whereas 2 input nodes denote the current current distance from the goal and angle.
Neural network used here is a sequential neural network model which is best suited when network layers do not need to interact with each other and there is only one tensor output.

for more info please go through the implementation report.


### Installation
* Git clone this repo [here](https://github.com/mananjethwani/motion_planning_neural_network).
* Move into the folder from your terminal:
```sh
    cd motion_planning_neural_network
```
* Run `pip3 install pygame numpy keras tensorflow jupyter` to install dependencies.
* Use `jupyter notebook`, open `Gridworld-I.ipynb` and run all commands line by line.