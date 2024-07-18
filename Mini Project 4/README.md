# **📘 Mini Project 4**

## **📖 Mini Project Overview**
Welcome to the fourth Machine Learning Mini Project. This mini project implements a classic AI problem, the Wumpus World, using two reinforcement learning techniques: Q-Learning and Deep Q-Network (DQN). This part includes the code, datasets, and reports for the mini-project. Detailed instructions and requirements for each part are provided below.

### **🔗 Link:**
- [Google Drive Link](https://drive.google.com/drive/folders/1oFh5an35Q6h42DEsNA36EbEkoOJjOI_l?usp=sharing)

---

## **🚀 Mini Project Tasks**

### ❓ **Question (Q1): the Wumpus World agent using Q-Learning and DQN**

#### **✏️ Task 1:Q-learning Implementation**

-**Environment Setup:** Initialize the Wumpus World environment using a 4x4 grid.  Define the observation space and action space, including movements and shooting actions.
-**Algorithm Implementation:** Implement the Q-learning algorithm. Define the Q-table, reward structure, and learning parameters. Ensure the agent can learn to navigate the environment and avoid hazards.
-**Training and Evaluation**: Train the agent using Q-learning and evaluate its performance. Adjust the parameters as needed to improve learning efficiency and reward.

---

#### **✏️ Task 2:DQN Implementation**

-**Network Architecture:** Define the architecture for the Deep Q-Network, including input layers, hidden layers, and output layers. Use appropriate activation functions and optimizers.
-**Replay Buffer:** Implement a replay buffer to store experiences and use them for training.
-**Training Process:** Train the DQN agent using the experiences stored in the replay buffer. Periodically update the target network to stabilize training.
-**Evaluation:** Evaluate the performance of the DQN agent and compare it with the Q-learning agent. Use cumulative reward to assess performance

---

## **📚 Libraries**

- `pandas`, `numpy`, `matplotlib`, `gym`, `tensorflow`, `keras`

## **📄 Report**
For more detailed information on the implementation, evaluation, and analysis of each question, please refer to the report file named MiniProject4-40207364.
