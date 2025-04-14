# 🟨 SDS_Deep Convolutional Q-Learning for Pac-Man

This project trains an AI agent to play Pac-Man using **Deep Q-Learning** with a convolutional neural network (CNN). The agent learns to navigate the environment, collect rewards, and avoid threats using reinforcement learning principles and deep neural network optimization.

---

## 📘 Project Overview

The Pac-Man agent is trained to:

- 🔍 Understand its current state (position, enemies, walls, and pellets)
- 🎮 Decide the best action (move up, down, left, right, or stay still)
- 💡 Learn from trial and error
- 💰 Maximize cumulative rewards (eating pellets and surviving)
- ❌ Avoid penalties (getting caught or hitting obstacles)

The model uses two neural networks:
- `local_qnetwork`: updated frequently as the agent learns
- `target_qnetwork`: serves as a stable reference during training

Experience replay is used to store and reuse past experiences, improving training stability and efficiency. The agent also uses an **epsilon-greedy policy** to balance exploration and exploitation during learning.

---

## ▶️ Run the Project in Google Colab

No installation is needed — just open and run in the cloud:

👉 **[Open in Colab](https://colab.research.google.com/drive/1X9voQzKrqIAe-lnYUU6K3wqMpW-5oFBg#scrollTo=MzeAILGk8B4O)**

---

## 🧠 Key Concepts Covered

- ✅ Deep Q-Learning (DQN)
- ✅ Convolutional Neural Networks (CNNs) for state representation
- ✅ Experience Replay Buffer
- ✅ Epsilon-Greedy exploration strategy
- ✅ Epsilon decay and exploration control
- ✅ Target and local networks
- ✅ Soft updates via interpolation
- ✅ Q-value prediction using PyTorch
- ✅ Automatic model saving upon performance threshold
