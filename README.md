# Multi-Armed Bandit

![Bandit Training Animation](https://github.com/galenwilkerson/galenwilkerson.github.io/blob/master/multi_armed_bandit.gif)

This repository demonstrates a **multi-armed bandit** setup, one of the simplest yet most fundamental reinforcement learning problems. The code implements an **ε-greedy** strategy, showing how an agent balances exploration of different arms against exploitation of the best-known arm.

## Overview
- **Notebook/Code**: [Multi-Armed-Bandit](https://github.com/galenwilkerson/Multi-Armed-Bandit/edit/main/)
- **Algorithm**: ε-greedy
- **Environment**: Each arm has a normally distributed reward with an unknown mean.

## Key Concepts
1. **Multi-Armed Bandit**: Imagine multiple slot machines (arms), each with an unknown payoff distribution.
2. **Exploration vs. Exploitation**: The agent must experiment with different arms (exploration) while also exploiting the arm that seems best.
3. **Reward Update**: After pulling an arm, the agent updates its estimated reward for that arm using incremental averaging.

## Running the Code
1. Clone or download this repository.
2. Install dependencies (e.g. `numpy`, `matplotlib`, `ipython`).
3. Open and run the notebook/code in Jupyter:
   ```bash
   jupyter notebook
