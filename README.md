# Soft Actor-Critic (SAC) – Reinforcement Learning

This project focuses on implementing and training a **Soft Actor-Critic (SAC)** agent, a modern off-policy reinforcement learning algorithm that combines **maximum entropy reinforcement learning** with efficient policy updates.  
The goal is to enable the agent to learn optimal behaviors through interaction with a simulated environment.

## 📊 Dataset / Environment
Unlike supervised learning tasks, this project does not rely on a fixed dataset.  
Instead, the **agent learns by interacting with the environment**, collecting state–action–reward–next state tuples during training. These experiences are stored in a **replay buffer**, which is sampled to update the policy and value networks.

The environment provides continuous state and action spaces, making SAC particularly suitable for this task.

## 🧠 Algorithm
The **Soft Actor-Critic** algorithm is used to train the agent.  
SAC improves exploration and stability by **maximizing expected return while also maximizing entropy**, encouraging diverse behaviors and avoiding premature convergence.

 
📅 *Spring 2025*
