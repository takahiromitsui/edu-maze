# 1. Configuration from txt file

Date: 2023-02-28

## Status

Proposed

## Context

In current setups, the main.py file defines parameters, such as screen size and the number of columns, for the EduMaze app. Therefore, developers must rewrite the main.py to change the screen size. It is not flexible, and configuration files should set up those parameters.

## Decision

I propose to create configuration txt files to store settings and read them with "configparser" on the main.py.

## Consequences

We need to import "configparser" on the main.py.
