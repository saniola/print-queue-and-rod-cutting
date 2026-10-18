# Print Queue and Rod Cutting

Two independent Python algorithm demonstrations: greedy 3D-print job scheduling and the classic rod-cutting dynamic programming problem.

## Contents

### `task1.py` — 3D Print Queue Optimization

Greedily groups print jobs into print runs that respect a printer's volume and item-count constraints, processing higher-priority jobs first (ties broken by longer print time) and reporting the resulting print order and total time.

### `task2.py` — Rod Cutting Problem

Solves the rod-cutting optimization problem (maximize profit from cutting a rod of given length into pieces, given a price per piece length) using two approaches:

- `rod_cutting_memo` — top-down dynamic programming with memoization.
- `rod_cutting_table` — bottom-up dynamic programming with tabulation.

Both return the maximum profit, the list of cuts, and the number of cuts.

## Stack

- Python 3 (standard library only)

## Usage

```bash
python task1.py
python task2.py
```
