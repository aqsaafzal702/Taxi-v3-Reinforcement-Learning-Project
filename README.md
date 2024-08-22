# Taxi-v3-Reinforcement-Learning-Project

This project involves training a reinforcement learning agent to navigate the Taxi-v3 environment using Q-learning. The goal is for the taxi to pick up passengers and drop them off at their destinations in the shortest possible time, minimizing penalties for illegal actions.

## Key Features
- **Environment**: Taxi-v3 from Gymnasium, a grid-based 5x5 environment.
- **Algorithm**: Q-learning with epsilon-greedy policy for exploration and exploitation.
- **Training**: The agent was trained over 2000 episodes with epsilon decay to balance exploration and exploitation.
- **Visualization**: The agent's behavior was captured and saved as a GIF for visualization.

## Setup
To run this project, you'll need to install the required libraries:

```bash
pip install gymnasium[toy_text] imageio
