## Overview

This work is based on Gymnasium environment.
Please refer https://gymnasium.farama.org/environments/box2d/lunar_lander/ for details




## Deep Q-Learning for Lunar Landing

### Need to install following packages (Setup)
Installing Gymnasium

pip install gymnasium
pip install "gymnasium[atari, accept-rom-license]"
brew install swig
apt-get install -y swig
pip install gymnasium[box2d]

Installing pythong libaries

os
random
numpy
pip3 install torch torchvision
collections

### Building the AI (Implementation - refer lunar_lander.py)
Creating the architecture of the Neural Network

### Training the AI
Setting up the environment

Initializing the hyperparameters

Implementing Experience Replay

Implementing the DQN class

Initializing the DQN agent

Training the DQN agent

### Visualizing the results (Demo - refer video_demo.py)

 
