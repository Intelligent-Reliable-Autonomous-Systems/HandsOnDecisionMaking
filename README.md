# Hands-On Decision-Making

This repository of Colab notebooks was created for the Fall 2024 Hands-On Decision-Making study group at Oregon State University. They cover introductory topics related to reinforcement learning and sequential decision-making. See how RL concepts are implemented and visualize how code modifications affect behavior.

## Topics

### Exploration 1: Markov Decision Processes and Gymnasium Environments

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Intelligent-Reliable-Autonomous-Systems/HandsOnDecisionMaking/blob/main/Exploration1_MazeMDP.ipynb)

This notebook:
- Describes the structure of a Markov Decision Process.
- Implements an MDP for a maze example.
- Gives a playground to interact with the Gymnasium reinforcement learning interface and example environments.
- Creates a Gymnasium wrapper around the maze MDP.
- Visualizes the actions of a random agent and an optimal agent.

Then you can get hands-on tweaking the reward function and transition function.

### Exploration 2: Value Iteration

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Intelligent-Reliable-Autonomous-Systems/HandsOnDecisionMaking/blob/main/Exploration2_ValueIteration.ipynb)

This notebook:
- Uses Gymnasium wrapper around the maze MDP from **Exploration 1**.
- Gives a visualization of the propogation of values through iterations of Bellman backups.
- Allows visualiaztion of agent following optimal policy from value iteration to solve the maze and reach goal.
- Offers variations and visualizations with larger grid world mazes.

You can play around with the maze layouts and walls to visualizse value propogations through iterations and agent behaviour.

### Exploration 3: Policy Evaluation and Improvement

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Intelligent-Reliable-Autonomous-Systems/HandsOnDecisionMaking/blob/main/Exploration3_PolicyEvalIter.ipynb)

This notebook:
- Provides a simplified implementation of value iteration on a grid maze and visualization of policy as a heatmap.
- Offers implementation and comparison of policy iteration in both, iterative and matrix (single-shot) form.  
- Visualizes comparison of polices from value iteration and policy iteration.

You can play around with the size and layout of the maze visualizse difference in policies from both, value and policy iteration.

## Contributors

Skand Peri, Jeff Jewett, Will Solow, Pulkit Rustagi, Yashwanti Anand
