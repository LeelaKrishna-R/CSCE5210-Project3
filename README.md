# CSCE5210 Project3: MDP Parallel Parking

## Overview
Implements Markov Decision Process (MDP) using Value Iteration to solve a parallel parking problem where an AI agent learns to safely navigate and park while avoiding hazards.

## Environment
- **Grid**: 8×5 cells
- **Goal**: Green cell at (1,3)
- **Hazards**: Red cells at (1,1) and (1,5)
- **Starts**: S1-S7 along bottom row
- **Noise**: 0.1 | **Discount**: γ = 0.99

## Requirements
```python
numpy
matplotlib
```

## Key Results
- **Optimal Live-in Reward**: r = -20
- **Policy P1**: Original environment strategy
- **Policy P2**: Strategy with obstacle at (3,4)
- **Differences**: 2 positions changed due to obstacle

## Usage
Run Jupyter notebook cells sequentially from setup through analysis.
