# IA

This repository contains implementations of various AI algorithms.

## Search Algorithms

The `Search_Algorithms` directory contains implementations of search algorithms including:
- A* (with different heuristics)
- BFS (Breadth-First Search)

### Running the Search Algorithms

You can run the search algorithms demo in two ways:

1. **Direct execution from the project root:**
   ```bash
   python Search_Algorithms/Main.py
   ```

2. **Module execution from the project root:**
   ```bash
   python -m Search_Algorithms.Main
   ```

Both methods will execute the same program and produce the same output.

### Project Structure

```
Search_Algorithms/
├── __init__.py
├── Main.py              # Main entry point
├── Algorithm/           # Algorithm implementations
│   ├── __init__.py
│   ├── Algorithm.py     # Base algorithm class
│   ├── Astar.py        # A* algorithm
│   └── BFS.py          # BFS algorithm
├── Heuristics/         # Heuristic functions
│   ├── __init__.py
│   └── Heuristica.py
├── Problem/            # Problem definitions
│   ├── __init__.py
│   └── Jogo8/          # 8-puzzle game
│       ├── __init__.py
│       ├── Acao.py
│       ├── Complexidade.py
│       ├── Estado.py
│       └── Jogo8.py
└── Tree/               # Tree data structures
    ├── __init__.py
    └── Arvore.py
```
