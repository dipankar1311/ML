# Reinforcement Learning (RL)
## Overview
RL is a type of ML where an agent learns to make decisions by interacting with an environment. The agent receives rewards or penalties based on its actions, and its goal is to maximize its cumulative reward over time.

## Key components of RL
Agent: the entity that learns and makes decisions

Environment: the world agent intracts with

State: current state of the agent within the environment

Action: decisions the agent can make

Reward: numerical value indicating the outcome of an action

## RL process / step
Initialization: The agent starts in an initial state

$Action: The agent chooses an action based on its current state and policy

Transition: The environment transitions to a new state based on the agent's action

Reward: The agent receives a reward based on its action and the new state

Update: The agent updates its policy to improve its future decisions

## RL types
Model based: The agent learns a model of the environment to predict future states and rewards

Model-free: The agent learns directly from experience without building a model of the environment

Reinforcement learning is a powerful tool for solving complex problems where traditional machine learning techniques may not be sufficient

## Common RL algorithms
### Value-based methods
Q-learning: A popular algorithm that learns the Q-value function, which estimates the expected future reward for taking a specific action in a given state

SARSA (State-Action-Reward-State-Action): Similar to Q-learning, but uses on-policy learning, meaning the agent follows its current policy while learning

Deep Q-learning: Combines Q-learning with deep neural networks for handling large state and action spaces

### Policy-based methods
Policy gradient: Optimizes the policy directly to maximize expected rewards

Actor-Critic: Combines value-based and policy-based methods, using both a value function and a policy

### Other
Monte Carlo methods: Learn from complete episodes of experience

Temporal Difference (TD) learning: Learn from incomplete episodes by bootstrapping estimates


