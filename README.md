# DSAI-Lab-AI-Project

Single-player Pong against a wall, written in Python turtle as the environment for a reward-based AI agent (NTU data science and AI lab, 2024).

[![Python](https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
![NTU](https://img.shields.io/badge/NTU-DSAI%20lab-1F3A93?style=flat-square)

## What it does

`environment.ipynb` is the game the agent was meant to learn: one paddle on the left, balls bouncing off the other three walls, and a new ball (in a new colour) every three paddle hits. Each hit scores the number of balls still in play, a missed ball is lost, and the round ends after 60 seconds (win) or when every ball is gone (lose). This repository holds step 1 of the plan below, the environment; the training code is not in it.

## Tech

Python 3, the standard-library `turtle`, `random` and `time` modules, Jupyter.

## Run

```bash
pip install notebook
jupyter notebook environment.ipynb   # run both cells; a 500x600 window opens
```

Move the paddle with `w` (up) and `d` (down). `turtle` needs a desktop display (Tk).

## Plan

Coding an AI that can play a modded version of single player pong against a wall. 
- Step 1: Code an environment
- Step 2: Train a reward based AI model
- Step 3: Maximise the score!
