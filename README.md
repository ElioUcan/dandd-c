# D&D — Text Adventure in C

## 🛠️ Technologies
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

## ✨ Features
- Multiple decision branches with nested choices across 3+ decision points
- 2 win conditions and 2 lose conditions depending on player choices
- Boolean inventory system: a key found mid-game unlocks a boss room gate
- Enemies, traps, and treasure encounters with branching outcomes
- Each game segment organized into named functions for readability
- Written in pure C using `if/else`, `switch`, standard I/O, and boolean flags

## 🎯 Uses
Text-based dungeon crawler built as a collaborative C programming exercise (Elio, Nahum, Veronica). The game teaches branching control flow, `switch` statement fallthrough, boolean state tracking, and function decomposition in C — all through a playable dungeon narrative.

## 🔧 Process
Designed the dungeon story as a branching decision tree first, then implemented each branch as a `switch`/`if` block in C. A single `llave` (key) boolean flag carries inventory state across function calls. A recurring bug during development — `switch` fallthrough without `break` statements — is documented in the source code comments as a learning note for future readers.

## 💡 Learnings
- `switch` fallthrough in C is silent and common: every `case` inside a `switch` needs a `break`, even when an `if` block is nested inside it
- Boolean flags are a simple but effective way to track inventory state across a branching game without a full data structure
- Organizing a long branching game into functions per room makes the code readable and lets each team member own a segment

## ▶️ Running the project

```bash
gcc -o dungeon "ProyectoD&DElioNahumVeronica.c"
./dungeon
```
