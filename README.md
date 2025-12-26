🐍 Snake Game Using Reinforcement Learning
📌 Overview

This project implements the classic Snake and Food game using Reinforcement Learning (RL), where an intelligent agent learns to play the game by interacting with the environment. The agent improves its performance over time by maximizing rewards through trial-and-error learning.

The goal of the agent is to eat food, grow longer, and avoid collisions with walls and its own body. This project demonstrates key RL concepts such as state representation, action selection, reward engineering, and policy optimization.

🎯 Objectives

Train an AI agent to play the Snake game autonomously

Understand reinforcement learning fundamentals

Design effective reward functions

Analyze agent performance over multiple episodes

🧠 Reinforcement Learning Approach

State Space: Position of snake head, food location, direction, and danger zones

Action Space: Move Left, Right, Up, Down

Reward Function:

+10 for eating food

-10 for collision (game over)

Small negative reward for each move to encourage efficiency

Algorithm Used:

Q-Learning / Deep Q-Network (DQN)

🚀 Features

Classic Snake game environment

Reinforcement learning–based AI agent

Real-time gameplay visualization

Training over multiple episodes

Performance tracking and learning curves

Modular and clean code structure

🛠️ Tech Stack

Python

NumPy

Pygame

TensorFlow / PyTorch (for DQN, if applicable)

Matplotlib (for result visualization)
