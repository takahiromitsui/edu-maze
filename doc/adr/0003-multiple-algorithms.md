# 3. Multiple algorithms

Date: 2023-02-28

## Status

Proposed

## Context

The current setup allows us to solve a maze with just one algorithm. We should add multiple algorithm options to solve a maze(e.g., random search, depth-first search, breadth-first search and so on).

## Decision

I propose to add "if" statements(options) to the"
_solver_r" function on the maze.py allows users to run different algorithms.
Example code as below.

```bash
  def _solver_r:
        algorithm = sys.argv[2]  # you specify this in the terminal

        # random search
        if algorithm == "RS":

        # depth-first search 
        if algorithm == "DFS":
```
And then catch the option when users run a command (e.g., python main.py RS).

## Consequences

We need to write multiple logic, and it takes some time.
