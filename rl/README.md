# Reinforcement Learning (RL)
## Overview
RL is a type of ML where an agent learns to make decisions by interacting with an environment. The agent receives rewards or penalties based on its actions, and its goal is to maximize its cumulative reward over time. It is inspired by behavioral psychology and involves learning through trial and error.

## Key components of RL
Agent: the entity that learns and makes decisions

Environment: the world agent intracts with

State: current state of the agent within the environment

Action: decisions the agent can make

Reward: numerical value indicating the outcome of an action

Policy (π): A strategy used by the agent to determine the next action based on the current state

Value Function (V): A function that estimates the expected cumulative reward from a given state, following a particular policy

Q-Function (Q): A function that estimates the expected cumulative reward from a given state-action pair, following a particular policy

## RL process / step
Initialization: The agent starts in an initial state

Action: The agent chooses an action based on its current state and policy

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
	• Updates the Q-value based on the Bellman equation.
	• Q(s, a) ← Q(s, a) + α [r + γ max Q(s', a') - Q(s, a)]
		• α: Learning rate
		• γ: Discount factor for future rewards

SARSA (State-Action-Reward-State-Action): Similar to Q-learning, but uses on-policy learning, meaning the agent follows its current policy while learning

Deep Q-learning: Combines Q-learning with deep neural networks for handling large state and action spaces
	• Uses deep neural networks to approximate the Q-function.
	• Handles high-dimensional state spaces, such as images.

### Policy-based methods
Policy gradient: Optimizes the policy directly to maximize expected rewards
	• Directly optimize the policy by adjusting the parameters to maximize expected reward.
	• Examples: REINFORCE algorithm, Proximal Policy Optimization (PPO).

Actor-Critic: Combines value-based and policy-based methods, using both a value function and a policy
	• Combine value-based and policy-based methods.
	• Use two models: an actor (policy) and a critic (value function).

### Other
Monte Carlo methods: Learn from complete episodes of experience

Temporal Difference (TD) learning: Learn from incomplete episodes by bootstrapping estimates


