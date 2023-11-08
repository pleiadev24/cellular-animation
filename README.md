## Background

Conway's Game of Life is a fascinating cellular automaton devised by the mathematician John Conway. It operates on a grid of cells, where each cell can be in one of two states: alive or dead. The cells evolve over discrete time steps according to the following rules:

A living cell with fewer than two living neighbors dies (underpopulation).
A living cell with two or three living neighbors survives.
A living cell with more than three living neighbors dies (overpopulation).
A dead cell with exactly three living neighbors becomes alive (reproduction).

## Installation

To run the cellular animation, make sure you have the following Python packages installed:


```bash
pip install numpy pygame argparse matplotlib
```

## Usage

Clone the repository and run the animation script:

```bash
python cellular_animation.py
```


This repo consists of two scripts/implementations
One uses numpy and matplotlib and other uses Pygame to create an interactive visualization of Conway's Game of Life. Enjoy exploring the mesmerizing patterns that emerge from these simple rules!

![output](https://github.com/rohinimohan14/cellular-animation/blob/main/cellular.png)


