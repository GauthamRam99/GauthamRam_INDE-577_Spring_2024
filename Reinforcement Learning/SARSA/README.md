# SARSA for Reinforcement Learning

This notebook demonstrates the implementation and explanation of SARSA (State-Action-Reward-State-Action), a classic reinforcement learning algorithm used for training agents to navigate grid-world environments.

## Overview

SARSA is an on-policy Temporal Difference (TD) learning algorithm that learns the value of state-action pairs by updating estimates based on observed transitions. It is particularly well-suited for environments with discrete action spaces, such as grid-worlds. SARSA iteratively learns an action-value function by sampling trajectories, updating Q-values based on observed transitions, and improving the policy towards the optimal policy.

## Notebook Contents

The notebook includes:

- Introduction to SARSA algorithm
- Implementation of SARSA in a grid-world environment
- Training an agent to navigate the grid-world
- Visualization of agent's policy and value function
- Evaluation of agent's performance

## Dependencies

To run the notebook, you'll need the following dependencies:

- Python 3.x
- Reinforcement learning libraries (e.g., OpenAI Gym)
- Data visualization libraries (e.g., Matplotlib)

## Dataset

SARSA does not require a pre-defined dataset like supervised learning algorithms. Instead, it learns directly from interaction with the environment. The grid-world environment provides states, rewards, and possible actions to the agent, and the agent learns from this experience to improve its policy.

## Author

This notebook is authored and maintained by Gautham Ram. If you have any questions, suggestions, or contributions, feel free to reach out.
