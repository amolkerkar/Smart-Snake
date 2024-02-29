# Smart Snake
This repository consists of two main components: a classic Snake game implemented in Python using the Pygame library and a reinforcement learning agent trained to play the game using the Q-learning algorithm.

:snake: :brain: :100:![image](https://github.com/amolkerkar/Smart-Snake/assets/81116875/f84c8281-3d7c-4ce3-8f9d-98d1c44fc671)

## Features:
The game is implemented using the Pygame library, providing a graphical interface.
The snake moves in four directions: up, down, left, and right.
The game keeps track of the player's score, which increases every time the snake consumes food.
Game over occurs when the snake collides with the boundaries of the screen or with itself.
### Reinforcement Learning Agent
* The reinforcement learning agent is trained to play the Snake game autonomously using the Q-learning algorithm.
* It observes the state of the game, takes actions (moves), and receives rewards based on its performance.
* Over time, the agent learns to maximize its cumulative reward, resulting in improved gameplay.

Key Components:

* The agent's state representation includes information about the snake's position, direction, proximity to walls, and the location of food.
* The agent learns from its experiences using a memory buffer to store state-action-reward-next state tuples.
* It utilizes a neural network model to approximate the Q-values for each action in a given state.
* Training occurs through iterative gameplay sessions, adjusting the model's parameters to optimize its performance.
