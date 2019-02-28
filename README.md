[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

This is my submission for Udacity project navigation. Following is the description of project:

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

- Clone the repository. Download python 3.6 and Pytorch 1.0.

- Install the unity environment as described here: [Getting Started section](https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md) (The Unity ML-agant environment is already configured by Udacity)

- The current repo has the environment for MAC. If you are using any other operating system download the corresponding build. If so, the code needs to be updated to point to the downloaded environment.

### Training and testing the agent

- The Navigation.ipynb can be executed to train/test the agent. The agent checkpoint is saved as nav_agent_checkpoint.pth. You can skip the training part and directly jump to the last cell to load the checkpoint and see the trained agent perform the navigation task.

### Request

- I am building a library for doing reinforcement learning. The rllib folder is another embedded repository. It would be updated time to time. All my three projects are using the same repo. If you are interested in collaborating, you can fork it and contribute. I would be very grateful for your contributions.


