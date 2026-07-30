# DEATH MINE

A first-person 3D horror game made with Unity. You wake up trapped in a dark, abandoned mine — the exit is blocked by fallen rocks, and something is hunting you in the tunnels. Restore the power, solve the puzzles and escape through the emergency exit before it finds you.

## Gameplay

- Explore the mine and find a way out
- The main exit is blocked — you must open the emergency exit:
  1. Find 3 fuses and start the generator
  2. Activate Panel 01 (15-slide puzzle)
  3. Activate Panel 02 (Sudoku puzzle)
  4. Find the code hidden on posters and enter it
  5. Find the keycard and escape through the emergency exit
- A zombie roams the tunnels — if it catches you, you die
- Jump scares, screamers and creepy ambient sounds throughout the mine

## Controls

| Key | Action |
|---|---|
| W A S D | Move |
| Mouse | Look around |
| Left Shift | Sprint |
| Left Ctrl | Crouch |
| Space | Jump |
| E | Interact |
| Esc | Pause / Resume |

## Features

- **Menu system** — main menu, loading screen, pause, death and escape screens
- **Objective system** — on-screen objectives that guide the player step by step
- **Puzzles** — 15-slide puzzle, Sudoku and a poster code lock with a randomly generated code each run
- **Zombie AI** — NavMesh-based enemy that patrols and chases the player
- **Screamers** — triggered jump scares with camera shake and sounds
- **First-person controller** — sprint, crouch, jump and footstep sounds

## Built With

- Unity **2022.3.62f3** (LTS)
- Universal Render Pipeline (URP) 14.0.12
- TextMesh Pro
- Unity NavMesh (AI Navigation)

## Getting Started

1. Clone the repository:
   ```
   git clone git@github.com:IslamAbdurahman/HorrorGame.git
   ```
2. Open the project in **Unity 2022.3.62f3** (or a newer 2022.3 LTS version)
3. Open the scene `Assets/LoafbrrAssets/MInesAndCaveSet/TestDemo.unity`
4. Press **Play**

## Project Structure

```
Assets/Scripts/
├── GameManager/      # Game state, objectives, menu system
├── Player/           # Movement, mouse look, health, interaction
├── Interactibles/    # Generator, fuses, panels, keycard, doors
├── 15PuzzleGame/     # Slide puzzle
├── SudokoGame/       # Sudoku puzzle
├── InputCode/        # Poster code lock
├── Screammers/       # Jump scares and scare effects
└── ZombieEnemy/      # Zombie AI
```
