## Taxi-v3 Q-Learning

## Project Description

This project implements the Q-Learning algorithm to train an agent to optimize its performance in the OpenAI Gym Taxi-v3 environment. The goal is to train a taxi driver to pick up and drop off passengers at designated locations efficiently while avoiding penalties. The Q-Learning algorithm is used to learn an optimal policy through trial and error.

## Implementation Details

- **Environment:** OpenAI Gym Taxi-v3  
- **Algorithm:** Q-Learning  
- **Libraries Used:** gym, numpy, random, tqdm  
- **Hyperparameters:**  
  - Learning Rate (Alpha): 0.1  
  - Discount Factor (Gamma): 0.6  
  - Exploration Rate (Epsilon): 0.1  
  - Training Episodes: 100,000  

## Results

The model was trained over 100,000 episodes, updating the Q-table iteratively. The final policy led to improved decision-making, reducing penalties and optimizing the taxi's efficiency. Post-training, the agent was tested over multiple episodes to evaluate its performance in handling passenger pickups and drop-offs efficiently.
