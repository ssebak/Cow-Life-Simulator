
# 🐄 Cow Life Simulator - Version 1.0

![Cow Life Simulator Screenshot](Cow-Life-Simulator.jpg)

**Date:** March 7, 2026

---

## Overview
Cow Life Simulator is a simple simulation designed to explore how different environmental factors and settings affect a cow population.

The goal of the game is to experiment with life-affecting variables: Will the herd thrive and grow, will they face extinction, or can you find the perfect balance to maintain a stable population?

---

## Legend & Environment
The simulation field consists of a 50x50 grid (2,500 cells).

* **Green cell:** Fresh grass.
* **Grey cell:** Eaten/depleted grass.
* **White/Black symbol:** A hungry cow searching for food.
* **Yellow/Black symbol:** A cow currently eating.
* **Red/Black symbol:** A sick cow.
* **Blue cell:** Water (impassable).
* **Brown cell:** Rocks (impassable).

### Cow Behavior
* **Searching:** A hungry cow searches for grass within a 5x5 cell radius.
* **Movement:** If no grass is found, the cow moves in a random direction.
* **Eating:** When a cow finds grass, it stays stationary to eat. You can customize how long the eating process takes.

---

## Settings & Variables
You can customize the following parameters in real-time:

* **Starting Population:** Initial number of cows.
* **Grass Growth Time:** Seconds it takes for a cell to regrow grass.
* **Eating Duration:** Seconds a cow spends eating one cell of grass.
* **Starvation Limit:** How many seconds a cow can survive without food.
* **Reproduction Chance:** Probability (%) of successful breeding.
* **Illness Chance:** Probability (%) of a cow becoming sick.
* **Illness Fatality:** Probability (%) of a sick cow dying.
* **Maximum Age:** Lifespan of a cow in seconds (0 = off).

### Health & Reproduction
* **Illness:** A sick cow can still move, eat, and reproduce. After 25 seconds, the cow will either recover or die based on the "Illness Fatality" setting.
* **Breeding Requirements:** Two cows can reproduce if:
    1.  They are in adjacent cells.
    2.  At least one of the cows is currently eating.
    3.  Both cows are older than 10% of the set "Maximum Age" (or at least 50 seconds old if Max Age is set to 0).

**Population Cap:** The population is capped at **2,100 cows** to ensure stability and performance, accounting for the space taken by rocks and water.

---

## Features & Controls
* **Localization:** Support for multiple languages.
* **Save/Load:** Save your custom game settings to a file or load previously saved configurations.
* **Reset:** Restarts the simulation. This clears the field and resets the population while keeping your current settings.
* **Pause/Resume:** Use the "Pause" button to halt the simulation and "Resume" to continue.
* **Real-time Adjustments:** Change settings while the game is running to see immediate reactions.
* **Browser Focus:** The simulation automatically pauses if you switch browser tabs and resumes when you return.

Have fun and... **MOOOOOOO!** :)