# LunaPilot-AI

# 🛰️ LunaPilot AI: Deep Q-Learning for Lunar Landing

This project implements a **Deep Q-Network (DQN)** agent to autonomously land a spacecraft in the classic **LunarLander-v2** environment from [OpenAI Gym](https://www.gymlibrary.dev/environments/box2d/lunar_lander/). Using deep reinforcement learning, the agent learns to control the lander through trial and error, optimizing actions to ensure safe and efficient landings.

## 🚀 Project Highlights

- ✅ Trained a neural network to approximate Q-values for action selection.
- 🔁 Implemented **experience replay** and **target networks** for stable learning.
- 🧠 Applied **ε-greedy exploration** strategy for balanced learning and exploitation.
- 📈 Visualized training progress and average reward trends over episodes.
- 🎯 Achieved near-optimal policy learning with consistent landing success.

## 🛠️ Technologies Used

- Python
- PyTorch
- OpenAI Gym
- NumPy
- Matplotlib

## 📂 Structure

- `Deep_Q_Learning_for_Lunar_Landing_Complete_Code.ipynb`: Complete notebook with all code, visualizations, and results.

## 📌 Requirements

```bash
pip install gym[box2d] torch numpy matplotlib
```

## ▶️ How to Run

Simply run the notebook step by step in a Jupyter environment:

```bash
jupyter notebook Deep_Q_Learning_for_Lunar_Landing_Complete_Code.ipynb
```

## 🤖 Outcome

By the end of training, the agent is capable of executing smooth and reliable landings on the lunar surface using learned control strategies.

---
