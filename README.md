# Project 2: Continuous Control - Track ball

### Introduction

This project aimed at solving [Continuous control project at Udacity/Deep-Reinforcement-Learning](https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control).

The objective of the project is to train 20 copies of the same agent so that each agent with a double-jointed arm can maintain its position at the target location for as many time steps as possible. The agents must get an average score of +30 over 100 consecutive episodes, and over all agents.

![Trained Agent](files/results/track_s.gif?raw=true "Trained Agents")

A reward is provided for each step that the agent's hand is in the goal location. The original project page describes the reward is +0.1, but it seems +0.04 is the actual reward, and the number of steps in an episode is 1000, which makes the maximum reward 40.0.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applied to two joints. Every entry in the action vector should be a number between -1 and 1.

### Getting Started

1. To setup the basic environment, please follow the instruction below.
 - https://github.com/udacity/deep-reinforcement-learning/blob/master/README.md
 - https://github.com/udacity/deep-reinforcement-learning/blob/master/p2_continuous-control/README.md

2. After you can successfully run [Continuous_Control.ipynb](https://github.com/udacity/deep-reinforcement-learning/blob/master/p2_continuous-control/Continuous_Control.ipynb) on your environment, clone the repository.

3. Copy the Reacher.app file at `p2_continuous-control/` into the `p2-ball-tracking/` folder. 

### Instructions

- [`TrainAgent.ipynb`](./TrainAgent.ipynb) trains agent and see the behavior of the trained agent.
- [`Report.ipynb`](./Report.ipynb) describes detailes of trained models, results and future ideas.