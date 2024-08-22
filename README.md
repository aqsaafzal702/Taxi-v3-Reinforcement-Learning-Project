# Taxi-v3-Reinforcement-Learning-Project
## About This Project
This project was completed as part of the [ Reinforcement Learning with Gymnasium in Python](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn) course on DataCamp.

## Certification
I have completed the Reinforcement Learning with Gymnasium in Python course on DataCamp. You can find the course completion certificate [here][(https://github.com/aqsaafzal702/Taxi-v3-Reinforcement-Learning-Project/blob/main/Reinforcement%20Learning%20with%20Gymnasium%20in%20Python.pdf)].

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
