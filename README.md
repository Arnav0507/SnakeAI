# Reinforcement Learning Snake 🐍

This project is a Deep Q-Learning (DQN) implementation to train an agent to play the classic Snake game using PyTorch and Pygame.

## Features

- **Deep Q-Learning Agent**: Learns to play Snake via rewards and punishments.
- **Customizable State Representation**: Includes food, wall, and self-collision awareness.
- **Pygame Visualization**: Watch the agent play in real time.
- **Training Plot**: Visualize the agent’s learning progress.

## Requirements

- Python 3.7+
- [PyTorch](https://pytorch.org/)
- [Pygame](https://www.pygame.org/)
- numpy

Install dependencies:
```sh
pip install torch pygame numpy
```

## How to Run

To play a random game (for testing):
```sh
python game.py
```

To train the agent:
```sh
python agent.py
```
Training progress and scores will be displayed in the terminal and plotted if you have matplotlib installed.

## Files

- `game.py` — The Snake game environment (Pygame).
- `agent.py` — The DQN agent and training loop.
- `model.py` — Neural network model and trainer.
- `helper.py` — Plotting utilities.

## Customization

- Tune hyperparameters in `agent.py` (learning rate, batch size, etc.).
- Adjust reward structure in `game.py` for different learning behaviors.
- Modify state representation in `agent.py` for richer agent perception.

## Credits

- Inspired by [PythonEngineer’s DQN Snake tutorial](https://www.youtube.com/watch?v=QfNvhPx5Px8).

---

Enjoy experimenting with RL and Snake!
