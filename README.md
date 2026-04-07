# PaperPlay

PaperPlay is a desktop suite of classic pen-and-paper style games built with **Python + Qt (PySide6)**.

## Games (v1)
- Tic‑Tac‑Toe
- Connect 4
- Nim
- Hangman
- Dots and Boxes
- Sudoku
- Nonogram (Picross)
- Crossword (player + editor)

## Requirements
- Python 3.10+

## Setup
```bash
# If `python` isn't found on Windows, use `py` instead.
py -m venv .venv
# Windows PowerShell:
.venv\Scripts\Activate.ps1
py -m pip install -U pip
py -m pip install -e ".[dev]"
```

## Run
```bash
py -m paperplay
```

## Tests
```bash
py -m pytest
```

## Crossword puzzles
Crosswords are saved as a **versioned JSON** file. See `[docs/CROSSWORD_FORMAT.md](docs/CROSSWORD_FORMAT.md)`.

