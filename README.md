# Gym-based FrozenLake-v1 Reinforcement Learning Project


## Overview
This project focuses on the FrozenLake-v1 environment, where an agent navigates a grid with frozen surfaces and holes to retrieve a chest. The task involves generating a random 10x10 valid grid with a 30% probability of a tile being frozen. The goal is to implement and train agents using reinforcement learning techniques.

## Game Elements

### Observations
The observations represent the current state of the environment, indicating the agent's position.

### Action Space
The action space defines the possible moves the agent can take, including up, down, left, and right.

### Reward
The reward system provides feedback to the agent based on its actions. Reaching the goal results in a positive reward.

### Environment's Info Dictionary
The environment's info dictionary contains additional information about the state and performance.

### Episode
An episode is a single run of the game, starting from the initial state until the agent reaches the goal or falls into a hole.

## Agent Implementation

### Design Choices
- Implemented a neural network-based agent.
- Used an 𝜀𝜀-greedy strategy for exploration.
- 𝜀𝜀 starts at 1 and decays to 0.1 during training.

### Adjusted Parameters
- Learning rate: Adjusted for optimal convergence.
- Neural network architecture: Fine-tuned layers and nodes for performance.

## Training Process 

### Experimental Setting
- High episode count due to the challenging nature of the game.
- Line plot visualizing average rewards over episodes.

## Improved Agent 

### Design Choices
- Added awareness of chest position.
- Agent remains unaware of hole positions initially.
- Detailed design rationale for transparency.

## Evaluation and Results 

### Comparison with Previous Agents
- Analyzed agent performance.
- Discussed the impact of additional information.

