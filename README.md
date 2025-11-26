# MsPacman-Atari-Domain
MsPacman Domain using AI techniques to improve play

# Project Overview

This project implements three agents:

1. Baseline DQN

A convolutional neural network producing Q-values for each discrete action.

2. Double DQN

Reduces Q-value overestimation by separating action selection and action evaluation.

3. Dueling DQN

Splits the network into Value and Advantage streams for more stable and expressive learning.

The agents are trained on:

Environment: ALE/MsPacman-v5

Observation: 84×84 grayscale, stacked 4 frames

Action Space: 5 discrete Atari actions

Objective: Learn to navigate the maze, avoid ghosts, and maximize score

## DQN MsPacman Agent Evaluation

Watch how performance improves as training progresses:

| Stage                                    | Video                                                                                                                         |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Early Training (random-ish behavior)** | <a href="https://github.com/MatthewAlvarez5/MsPacman-Atari-Domain/blob/main/DQN_Pacman_Early.mp4" target="_blank">▶ Watch</a> |
| **Late Training (learned behavior)**     | <a href="https://github.com/MatthewAlvarez5/MsPacman-Atari-Domain/blob/main/DQN_PacMan_Late.mp4" target="_blank">▶ Watch</a>  |


