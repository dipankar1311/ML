## Overview

This work is based on Gymnasium environment.
Please refer https://gymnasium.farama.org/environments/box2d/lunar_lander/ for details




## Deep Q-Learning for Lunar Landing

### Need to install following packages (Setup)
Installing Gymnasium

    pip install gymnasium

    pip install "gymnasium[atari, accept-rom-license]"

    brew install swig

    pip install gymnasium[box2d]

Installing pythong libaries

    os

    random

    numpy

    collections

    pip3 install torch torchvision
### Building the AI & Training the AI (Implementation - refer lunar_lander.py)

### Visualizing the results (Demo - refer video_demo.py)
Installing pythong libaries for video display

    glob
    io
    base64
    pip install imageio
    pip install imageio[ffmpeg]
    pip install imageio[pyav]
    pip install ipython

 
### Run
To train the agent (no video)
    python3 lunar_lander.py

To train the agent and demo with a nice video
    python3 video_demo.py
