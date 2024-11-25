

# 🚀 LunarLander REINFORCE 🪐

Welcome to the **LunarLander REINFORCE** project! This repository demonstrates the implementation of a reinforcement learning (RL) agent using the REINFORCE algorithm to control a lunar lander. 🌕✨

## 📚 Project Overview
This project trains an RL agent to:
1. Land the lunar module safely using optimal actions. 🌟
2. Maximize cumulative rewards over episodes. 🎯
3. Improve performance using policy gradients and neural networks. 🧠

## 🔧 Key Features
- **Environment:** LunarLander-v3 from Gymnasium. 🎮
- **Algorithm:** REINFORCE (Monte Carlo Policy Gradient). 📈
- **Frameworks:** Built with `JAX`, `Haiku`, and `Optax` for high-performance computation. ⚡
- **Visualization:** Tracks and plots rewards over episodes. 📊

## 🛠️ Setup Instructions
### 1️⃣ Install Dependencies
Run the following commands to install required libraries:
```bash
pip install jax jaxlib dm-haiku gymnasium matplotlib optax
```

### 2️⃣ Run the Code
Launch the training process:
```bash
python lunalander.py
```

### 3️⃣ Visualize Results
Check the plot of cumulative rewards at the end of training. 📉➡️📈

## 🧠 How It Works
1. **Policy Neural Network**: A multi-layer perceptron predicts action probabilities. 🖥️
2. **Policy Gradient Updates**: Improves the policy to maximize rewards. 🔄
3. **Discounted Returns**: Calculates future rewards at each timestep. ⏳

## 📊 Results
After training for ~8000 episodes, the agent learns to land successfully with high returns. Check out the final performance metrics and plots! 🎉
Video : https://github.com/user-attachments/assets/a42812e7-8887-4938-8646-8394b82e607e


## 🎯 Future Enhancements
- Experiment with different network architectures. 🛠️
- Apply to other environments like CartPole or BipedalWalker. 🤖
- Explore baseline variance reduction techniques. 🔬

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue. 📝

## 📝 Credits
- Adapted from **Deep Learning Indaba 2022** and **AIMS South Africa** workshops. 🌍
- Special thanks to Arnu Pretorius and the AIMS team. 🤝

---

Would you like to add any specific details or refine it further?
