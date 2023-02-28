# 2. Use another GUI toolkit

Date: 2023-02-28

## Status

Proposed

## Context

We utilise "tkinter" to visualise a maze in the current setup. To accelerate front-end development, we need another non-code GUI tool.

## Decision

I propose to use QT5 to create UIs.


## Consequences

QT5 generates python files based on your UI files and makes us easier to create new UIs.
However, we need to replace most of the UI classes on graphics.py and maze.py with QT5 components.
