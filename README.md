# Disclaimer

⚠️ This is a **personal utility script** — quick and minimal. It is provided **for self-use** and educational purposes. **Use at your own risk.** No guarantees are made regarding correctness or performance in any environments.


# Task Scheduling with OR-Tools

This repository provides a quick example of how to schedule a set of tasks with **precedence constraints** across multiple **bins** (e.g., workers or machines), using the **OR-Tools CP-SAT solver**. The goal is to **minimize the overall makespan** — the total time required to complete all tasks.

## Contents

- `schedule_solver.py`: Core logic for modeling the scheduling problem using OR-Tools.
- `example_runner.py`: A small script demonstrating usage with a sample task set.

## Features

- Handles task durations and prerequisites (precedence constraints).
- Distributes tasks across a user-defined number of bins.
- Optimizes for minimum makespan using constraint programming.
- Includes a simple visualization/Gantt-style output for validation.
- 
## Requirements

- Python 3.7+
- `ortools`
- `matplotlib` (optional, for visualization)
- `graphviz` (optional, for visualization; need to set `$PATH` so install with `brew` if on MacOS)
