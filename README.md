# Project: Mundane

**Genre:** 2D Simulation, Rhythm, Narrative Time-Loop  
**Engine:** Godot 4.x  
**Developers:** eitophetamine & flurger  

## High-Level Concept
Players take on the role of a blacksmith trapped within a time loop. The core objective is to manage a 2D blacksmithing shop by taking commissions, crafting items via rhythm-based minigames, and performing quality control. Over time, the mundanity of the job degrades the blacksmith's skill, which ties directly into the fate of a recurring hero and the progression of the time loop.

## Core Gameplay Mechanics
* **Commissions:** Accept daily requests from various customers for weapons and equipment to keep the shop running.
* **Crafting Minigame:** Craft items using a 2D rhythm-based mechanic (similar to osu!). Precision and timing dictate the final quality of the item.
* **Quality Control:** After crafting, inspect the item. The player must choose whether to sell the item as-is or scrap it and remake it if the quality falls below standard.
* **Day Counter:** The game tracks time linearly. The total number of days elapsed serves as the final score.

## Technical Systems 
* **State Manager / Loop Controller:** Tracks the current loop iteration, hero state (blind/undamaged), and day counter.
* **Rhythm Engine:** A custom framework to parse beatmaps/timing windows and calculate accuracy percentages for the crafting phase.
* **Difficulty Modifier:** A dynamic system that narrows the timing windows of the rhythm minigame based on the current narrative phase to simulate skill degradation.

## Getting Started (Development)
1. Clone this repository.
2. Open the **Godot 4.x** Project Manager.
3. Click **Import** and select the `project.godot` file located in the root directory.
4. Ensure you are working on your assigned branch before making changes to the scene tree.

## Contribution Guidelines
* **Main Branch:** Reserved for stable, playable builds. 
* **Feature Branches:** Create a new branch for specific features (e.g., `feature/rhythm-ui` or `feature/hero-dialogue`).
* **Commits:** Write clear, descriptive commit messages so we can track changes easily.
