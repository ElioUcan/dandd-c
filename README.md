# D&D in C — Text Adventure Game Engine

A text-based dungeon crawler game written in C. The player navigates a dark dungeon, making decisions at each room that determine their fate.

## Gameplay

You wake up in a dark dungeon and must find your way out. Each room presents choices that branch into different outcomes — some lead to victory, others to defeat.

```
You wake up in a dark dungeon. Two doors ahead.
> 1. Left door  →  sleeping dragon (sneak past or attack it?)
> 2. Right door →  locked chest   (pick the lock or leave it?)
```

## Features

- 3+ decision points with multiple choices each
- 2 win conditions and 2 lose conditions
- Inventory system (item/key tracking with boolean flags)
- Enemies, traps, and treasures
- Organized with functions for each game segment

## Tech Stack

- **C** — conditionals (`if`, `else if`, `else`, `switch`), functions, standard I/O

## Build & Run

```bash
gcc -o dungeon "ProyectoD&DElioNahumVeronica.c"
./dungeon
```

## Authors

Elio, Nahum, Veronica
