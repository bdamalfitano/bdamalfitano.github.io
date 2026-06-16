---
layout: page
title: "Othello Game"
permalink: /othello-game/
header-img: "img/city5.jpg"
tags:
  - Python
  - Minimax Algorithm
  - Alpha-Beta Pruning
  - AI
---

<style>
  header.intro-header {
    background-position: center 40%;
    height: 520px;
  }
</style>

<div class="project-tags">
  <span>Python</span>
  <span>Minimax Algorithm</span>
  <span>Alpha-Beta Pruning</span>
  <span>AI</span>
</div>

## Overview

Designed and implemented a fully playable Othello (Reversi) game in Python featuring a Minimax AI opponent with alpha-beta pruning and iterative deepening. The project supports both human vs AI and automated AI vs AI modes with configurable time budgets per move.

## Technologies Used

- Python  
- Minimax Algorithm  
- Alpha-Beta Pruning  
- Iterative Deepening  

## System Design Process

### Step 1 Board and Game Logic

The project began with implementing the core Othello rules:

- Board representation with BLACK, WHITE, and EMPTY states  
- Legal move generation and piece flipping logic  
- Win condition detection and score calculation  
- Turn management and pass handling  

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/othelloboard.png"
       alt="TV Shuffle Setup"
       style="max-width: 500px; width: 100%; height: auto;">
</div>

### Step 2 AI Agent Architecture

The AI was built around a modular agent system:

- Agent registry allowing multiple agent types to be swapped in and out  
- MinimaxAgent with alpha-beta pruning to eliminate losing branches early  
- Iterative deepening to search as deep as possible within a time budget  
- RandomAgent for benchmarking and self-play testing 

### Step 3 Game Modes and CLI

The game was made fully configurable through a command-line interface (CLI):

- Human vs AI mode with move input via board coordinates (e.g. d3, f5)  
- AI vs AI mode for automated self-play and performance testing  
- Multi-game batch runs with win/loss/draw summaries  
- Quiet mode to suppress per-move output during large batch runs  

## Key Features

- Playable Othello game with full rule enforcement  
- Minimax AI with alpha-beta pruning and iterative deepening  
- Configurable per-move time budget  
- Human vs AI and AI vs AI game modes  
- Modular agent system for easy swapping and testing  
- Multi-game batch runner with result summaries

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/othellobot.png"
       alt="TV Shuffle Setup"
       style="max-width: 500px; width: 100%; height: auto;">
</div>

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/othellogame.png"
       alt="TV Shuffle Setup"
       style="max-width: 500px; width: 100%; height: auto;">
</div>