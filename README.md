# Towers of Hanoi MDP: Value Iteration & Q-Learning

This project implements a Markov Decision Process (MDP) formulation of the Towers of Hanoi puzzle, with tabular Value Iteration and Q-Learning solvers. It is designed for educational purposes, specifically for CSE 415 at the University of Washington.

## Folder Contents
- `toh_mdp.py`: Core MDP logic for Towers of Hanoi, including state representation, operators, transition and reward functions.
- `solvers.py`: Implements tabular Value Iteration and Q-Learning solvers for the MDP.
- `solver_utils.py`: Utility functions for value iteration, policy extraction, Q-value updates, and exploration strategies.
- `gui.py`: Graphical user interface for visualizing the Towers of Hanoi MDP, policies, and agent actions.
- `autograder.py`: Autograder and test harness for validating your implementation against provided test cases.
- `test_cases/`: JSON files with test cases for value iteration and Q-learning (for 2, 3, and 4 disks).
- `a5_report.txt`: Written report answering assignment questions and explaining design choices.
- `__pycache__/`: Python bytecode cache (can be ignored).

## What Was Added
- Implementation of value iteration and Q-learning algorithms in `solver_utils.py`.
- Custom exploration and learning rate functions for Q-learning.
- Written answers and explanations in `a5_report.txt`.

## How to Use
1. **Run the GUI**: Launch `gui.py` to visualize the MDP and interact with the solvers.
   ```powershell
   python gui.py
   ```
2. **Run the Autograder**: Test your implementation with:
   ```powershell
   python autograder.py
   ```
   Use command-line flags for more options (see autograder source).
3. **Explore the Code**: Start with `toh_mdp.py` for the MDP logic, then look at `solvers.py` and `solver_utils.py` for the algorithms.
4. **Check the Report**: Read `a5_report.txt` for explanations of the algorithms and design decisions.

## For Newcomers
- The project models the Towers of Hanoi as an MDP, allowing reinforcement learning algorithms to solve it.
- Value Iteration computes optimal policies by iteratively updating state values.
- Q-Learning learns optimal actions through simulated experience and exploration.
- The GUI helps visualize states, policies, and agent progress.
- Test cases and the autograder help verify correctness.

## Requirements
- Python 3.7+
- Standard libraries only (no external dependencies required)

## Credits
- Assignment and starter code by University of Washington, CSE 415.
- Solutions and report by Nathan Vitzthum and Grace Liu.

---
For questions or further exploration, see the comments in each file and the report for more details.
