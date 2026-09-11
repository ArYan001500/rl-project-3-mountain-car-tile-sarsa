# RL project 3: Mountain Car with tile coding

This project applies tile coding and semi-gradient SARSA to Mountain Car.

## Contents

- `AIUT_Environments.py`: custom AIUT Mountain Car environment.
- `notebooks/aiut_mountaincar_tile_sarsa.ipynb`: tile coding with semi-gradient SARSA in the custom environment.
- `notebooks/gymnasium_mountaincar_tile_sarsa.ipynb`: Gymnasium MountainCar-v0 comparison.

## Results from the project notes

The custom AIUT Mountain Car run used 8 tilings with an 8x8 grid per tiling and trained for 5000 episodes. The reported learning curves converge toward roughly 130 to 140 steps per episode near the end. The Gymnasium version was trained for 500 episodes and reached roughly 149 steps after learning in the reported run.
