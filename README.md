# Project 2: Continuous Control

_Udacity Deep Reinforcement Learning Nanodegree_

![Smart agent](img/smart_agent.gif)

### Project details

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

To speed up the process of learning, this project uses distributed training - multiple (non-interacting, parallel) copies of the same agent distributes the task of gathering experience.

To solve the environment, the agents must get an average score of +30 over 100 consecutive episodes, and over all agents.

### Prerequisites

* [Miniconda](https://conda.io/miniconda.html)

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

    conda create --name drlnd python=3.6
    source activate drlnd
    git clone https://github.com/udacity/deep-reinforcement-learning.git
    cd deep-reinforcement-learning/python
    pip install .

### How to Run

Clone this repo, then run `jupyter notebook` to access the notebook.

### Notebook

[Link](Continuous_Control.ipynb)

### Report

[Link](report.md)
