# Reinforcement-Learning-Project
Electric Vehicle Charging Optimization Using Reinforcement Learning


Project Title

Electric Vehicle Charging Optimization Using Reinforcement Learning

Project Description

This project develops a PPO-based reinforcement learning agent that learns
when and how much to charge an electric vehicle under variable electricity
prices while attempting to achieve a required target state of charge before
departure.

Algorithm

Proximal Policy Optimization (PPO)

Environment

Custom Gymnasium electric vehicle charging environment.

State Variables

- Current SOC
- Electricity price
- Current time
- Remaining time before departure
- Target SOC

Action

Continuous charging power.

Reward

The reward penalizes electricity charging cost and failure to reach the
required target SOC.

Baseline Strategies

- Immediate Charging
- Rule-Based Low-Price Charging

Evaluation Metrics

- Total Charging Cost
- Target SOC Success Rate
- Final SOC
- Cumulative Reward
- Cost Savings
- SOC Shortfall
- Training Convergence

Tools

Python
Google Colab
Gymnasium
Stable-Baselines3
PyTorch
NumPy
Pandas
Matplotlib

How to Run

1. Open EV_Charging_Optimization_Part2.ipynb in Google Colab.
2. Run the installation cell.
3. Run all cells in order.
4. Train the PPO model.
5. Run the evaluation section.
6. Review the generated comparison tables and graphs.
