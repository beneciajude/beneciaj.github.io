---
layout: page
title: PacMan AI
permalink: /projects/pacman-ai/
description: A collection of AI projects exploring search, reinforcement learning, and probabilistic models — all within the Pacman world.
img: assets/img/200w.gif
importance: 1
category: software
tags: [AI, Python, CS188, Search, ML, HMM, Reinforcement Learning]
---

These projects were developed as part of UC Berkeley’s CS188: Introduction to Artificial Intelligence. Each project applies a core concept in AI using the classic Pacman game environment.

---

### 🧠 Project 1: Search
Implemented DFS, BFS, UCS, and A* search to solve maze navigation and traveling salesman problems.

### 🕹️ Project 2: Games
Developed multi-agent Pacman agents using minimax and expectimax for adversarial/stochastic environments.

### 🔁 Project 3: Reinforcement Learning
Trained agents via value iteration, Q-learning, and approximate Q-learning to learn optimal movement strategies.

### 👻 Project 4: Bayes Nets & HMMs
Used Bayes Nets and Hidden Markov Models to infer ghost locations from noisy distance readings.

### 🧠 Project 5: Machine Learning
Built and evaluated classifiers (Perceptron, NN, RNN) to perform digit classification and language ID.

---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/pacman-search.png" title="Search: A* solving a Pacman maze" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/pacman-qlearn.gif" title="Pacman learning with Q-Learning" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/pacman-hmm.png" title="Ghost tracking with Hidden Markov Models" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  Left: A* search navigating the maze. Middle: Q-learning in action. Right: Probabilistic ghost tracking with HMM.
</div>

You can check out code snippets, writeups, or demos for each module. Let me know if you’d like to collaborate on agent tuning, reward shaping, or extending the environments.

---
