# BlockBlast – Godot 4 Puzzle Game

A Block Blast style puzzle game built with **Godot 4.2+**.

## How to Play

1. **Drag** one of the 3 pieces at the bottom onto the 8×8 grid.
2. Pieces must fit in empty cells – they **cannot overlap**.
3. Fill a complete **row or column** to clear it and earn bonus points.
4. Place all 3 pieces to receive a fresh set.
5. The game ends when **no piece can be placed** anywhere on the board.

## Scoring

| Action | Points |
|---|---|
| Each cell placed | 10 pts |
| First line cleared | 80 pts |
| Second line (combo) | 160 pts |
| Each additional line | +80 pts more |

## Setup

### Requirements
- **Godot 4.2** or newer  
  Download from https://godotengine.org/download

### Running the Game

1. Open **Godot Engine**
2. Click **Import** → select the `project.godot` file in this folder
3. Click **Open** then **Import & Edit**
4. Press **F5** (or the ▶ Play button) to run

### Export (optional)
- Go to **Project → Export**
- Add your desired platform preset
- Click **Export Project**

## Project Structure

```
BlockBlast/
├── project.godot       # Godot project configuration
├── icon.svg            # App icon
├── scenes/
│   └── Main.tscn       # Main game scene
└── scripts/
    └── Main.gd         # All game logic (GDScript)
```

## Controls

| Input | Action |
|---|---|
| Click & Drag | Pick up and move a piece |
| Release | Place the piece |

## Tips & Tricks

- Plan ahead! Look at all 3 pieces before placing any.
- Try to clear multiple lines at once for big combo bonuses.
- Keep the board open – don't box yourself into a corner.

---
Made with ❤️ using Godot 4 GDScript
