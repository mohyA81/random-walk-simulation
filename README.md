# Random Walk Simulation with Python

## Overview

This project simulates repeated coin tosses using Python and NumPy. It tracks the cumulative number of tails in each game and visualizes the distribution of final results using Matplotlib.

## How It Works

* Generates random coin toss results using `np.random.randint()`.
* Tracks the cumulative number of tails during each game.
* Simulates 100 independent games, with 10 coin tosses per game.
* Stores the final result of each game.
* Uses a histogram to visualize the distribution of final results.

## Technologies

* Python
* NumPy
* Matplotlib

## What I Learned

* Generating random numbers with NumPy
* Using nested `for` loops
* Tracking cumulative values in a list
* Storing simulation results
* Visualizing distributions with a histogram

## How to Run

Install the required libraries:

```bash
pip install numpy matplotlib
```

Run the script:

```bash
python random_walk.py
```