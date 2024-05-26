# Policy and Value Iteration in a Grid World (Python)
This code implements the Policy and Value Iteration algorithms for solving a Reinforcement Learning problem in a 5x5 grid world.

## Environment:
The agent moves on a 5x5 grid with actions: up, down, left, right.
Rewards are placed at the end of each row (states 1 and 3).
The discount factor (gamma) is 0.9.
## Algorithm:
The code implements Policy Iteration, which iterates between:
1. Policy/Value Evaluation: Updating state values based on the current policy using the Bellman equation.
2. Policy/Value Improvement: Updating the policy to take the action with the highest expected value for each state.
