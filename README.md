# DQN Assignment 3

**Name:** Albright Maduka  
**Student ID:** 9053136  
**Course:** CSCN8020  
**Assignment:** Assignment 3  

## Overview
This repository contains a Jupyter Notebook implementation of a Deep Q-Network (DQN) agent applied to the Atari environment Pong using image-based input.

## Key Features
- Image preprocessing
- Frame stacking
- Deep Q-Network (CNN-based)
- Experience replay
- Target network
- Epsilon-greedy exploration
- Performance evaluation and comparison

## Experiments
The following configurations were evaluated:

- **Baseline:** Batch Size = 8, Target Update = 10
- **Batch Size Experiment:** 8 vs 16
- **Target Update Experiment:** 10 vs 3

Each experiment compares:
- score per episode
- average reward over the last 5 episodes
- total training steps

## Results
Results are saved in the `results/` folder:
- `baseline_results.csv`
- `batch16_results.csv`
- `target3_results.csv`
- `summary_table.csv`

## Final Recommendation
Based on the experimental results:

- **Batch Size:** 16
- **Target Update Frequency:** 3 episodes

## Limitations
The results are based on a relatively small number of training episodes (30). Performance may differ with longer training.

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook DQN_Assignment3.ipynb