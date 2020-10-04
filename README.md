# Project 1: Navigation

## Introduction
In this project an agent will be trained to collect bananas in a 2d squared world. The agents job is to collect yellow banans and possibly avoid blue banans. The yellow bananas give a +1 reward whereas the blue bananas give a -1 reward.

The agent can take four different actions:
- Move forward.
- Move backward.
- Move left.
- Move right.

The state space consists of 37 different states including velocity and the ray tracing perception of the agent's forward field of view. 

This is an episodic task becuase the episode will automaticly end after 299 time steps.

## Libraries needed
The following libraries need to imported in order to run all the cells in the notebook
-- UnityEnvironment from unityagents 
-- numpy
-- random
-- namedtuple and deque from collections
-- torch
-- matplotlib.pyplot
-- pandas as pd
