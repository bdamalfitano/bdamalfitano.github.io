---
layout: page
title: "Unity Game"
header-img: "img/city5.jpg"
tags:
  - Unity
  - C#
  - Game Development
  - Game Design
  - Agile
---

<style>
  header.intro-header {
    background-position: center 40%;
    height: 520px;
  }
</style>

<div class="project-tags">
  <span>Unity</span>
  <span>C#</span>
  <span>Game Development</span>
  <span>Game Design</span>
  <span>Agile</span>
</div>


## Overview

Designed and developed a 2D space shooter roguelike in Unity as part of a semester-long group project with a team of seven. The game follows a Space Invaders-inspired format where the player progresses through rooms, defeats waves of enemies, and collects coins to spend in an upgrade shop between stages.

The project followed a structured game development workflow across three milestone deliverables, with the team collaborating through Unity's built-in version control system using changesets to manage contributions from all members.


<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/unitygame.png"
       alt="UML Diagram"
       style="max-width: 700px; width: 100%; height: auto;">
</div>


## Technologies Used

- Unity  
- C# (MonoBehaviour Scripts)  
- Unity Plastic SCM (Version Control)  
- Unity Prefab System  
- Audio Design  
- 2D Sprite Assets  

## System Design Process

### Step 1 Project Planning and Milestones

The semester was divided into three milestone phases, each with defined deliverables and quotas:

- Core game loop and player movement established in Milestone 1  
- Enemy behavior, room progression, and coin system added in Milestone 2  
- Boss stages, shop system, polish, and audio completed in Milestone 3  

Weekly team coordination ensured tasks were distributed and deadlines were met across all seven members.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/changesets.png"
       alt="UML Diagram"
       style="max-width: 400px; width: 100%; height: auto;">
</div>

### Step 2 Core Game Systems

The gameplay was built around several interconnected systems:

- Player movement, shooting, and HP management  
- Enemy spawning with varied attack patterns  
- Room-based progression with wave clear conditions  
- Coin drop and collection system tied to the upgrade shop  
- Lives system that returns the player to the main menu on game over  

### Step 3 Unity Features and Collaboration

The team made extensive use of Unity's toolset to build and manage the project:

- Prefabs for enemies, projectiles, UI elements, and pickups  
- C# scripts for all game logic including combat, spawning, and shop interactions  
- Audio sources and clips for sound effects and background music  
- Unity Plastic SCM for pushing and merging changesets across the team  

## Key Features

- 2D Space Invaders-style roguelike with room-based progression  
- Enemy waves with boss stages at key intervals  
- Coin economy with an in-run upgrade shop  
- Lives system with full run reset on game over  
- Seven-person collaborative development using Unity version control  
- Three structured milestone deliverables across the semester

# Boss Scene:
<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/bossscene.png"
       alt="UML Diagram"
       style="max-width: 700px; width: 100%; height: auto;">
</div>