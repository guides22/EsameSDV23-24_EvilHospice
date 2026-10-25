# Evil Hospice

**Evil Hospice** is a 2D top-down stealth-horror game prototype developed using Unity and C# as a university project for the *Video Game Development* course at the University of Bari, Italy, during the 2023–2024 academic year.

The game follows Bob, a retired secret agent living in a nursing home whose residents have mysteriously turned into zombies after taking an experimental medication. To survive, Bob must navigate the building, avoid enemies, and use limited resources to find his way out.

The project was developed as a **single-level playable prototype**, focusing on fundamental game development concepts such as player movement, enemy behavior, collision handling, inventory management, and level design.

## Gameplay

The player explores a pixel-art environment from a top-down perspective, navigating rooms and corridors while avoiding zombies.

Different enemy types have different movement speeds and damage values, encouraging the player to choose suitable paths and manage resources carefully.

### Features

- **Top-down movement:** Explore the environment using WASD controls.
- **Enemy encounters:** Avoid zombies with different movement speeds and damage values.
- **Health system:** Survive enemy attacks while managing the player's four health points.
- **Inventory system:** Collect and use consumable items found throughout the level.
- **Power-ups:** Restore health, temporarily increase movement speed, or gain protection against enemy attacks.
- **Game states:** Main menu, gameplay, victory, and game-over screens.
- **Pixel-art environments:** Explore indoor and outdoor areas of a zombie-infested nursing home.

## Screenshots

### Main Menu

![Evil Hospice Main Menu](docs/screenshots/main-menu.png)

### Gameplay — Starting Room

![Evil Hospice Starting Room](docs/screenshots/bedroom.png)

### Gameplay — Corridors

![Evil Hospice Corridor](docs/screenshots/corridor.png)

### Gameplay — Outdoor Area

![Evil Hospice Parking Lot](docs/screenshots/parking-lot.png)

## Download and Play

Precompiled builds for Windows and Linux are available in the repository's GitHub Releases section.

**[Download Evil Hospice — GitHub Releases](https://github.com/guides22/EvilHospice/releases)**

### Windows

1. Download the Windows ZIP archive from the Releases page.
2. Extract the archive.
3. Run the game's `.exe` file.

### Linux

1. Download the Linux ZIP archive from the Releases page.
2. Extract the archive.
3. Run the game executable.

If the executable does not have execution permissions, grant them using:

```bash
chmod +x <game-executable>
```

Replace `<game-executable>` with the actual executable filename.

## Controls

| Input | Action |
|---|---|
| W / A / S / D | Move the player |
| Left mouse button | Select and use inventory items |

## Technologies and Tools

| Technology | Purpose |
|---|---|
| **Unity 2022.3 LTS** | Game engine, scene management, physics, and gameplay |
| **C#** | Game logic and scripting |
| **Tiled** | Tilemap creation and level design |
| **LibreSprite** | Pixel-art creation and sprite editing |
| **Visual Studio Code** | C# development |

The project was originally developed with Unity `2022.3.28f1` and later updated to `2022.3.62f2` for compatibility and security maintenance.

## Project Structure

```text
EvilHospice/
├── Retirement_Evil/          # Unity project
│   ├── Assets/                # Scripts, scenes, sprites, audio, prefabs, etc.
│   ├── Packages/              # Unity package configuration
│   └── ProjectSettings/       # Unity project settings
├── docs/
│   ├── screenshots/           # Gameplay screenshots
│   └── GameDesignDocument.pdf # Original game design document
├── .gitignore
└── README.md
```

Standalone builds are distributed separately through GitHub Releases to keep the source repository focused on the Unity project and its documentation.

## Game Design Document

The original [Game Design Document (GDD)](docs/GameDesignDocument.pdf), written in Italian, describes the initial concept and design of Evil Hospice.

It includes:

- Story, setting, and characters.
- Gameplay objectives and mechanics.
- Player abilities, enemies, and consumable items.
- Level design and visual style.
- Technical tools and development choices.
- Ideas for potential future improvements.

The GDD describes the broader concept originally envisioned for the game, including features and content that were not implemented in the final prototype.

This README provides an English overview of the playable version and its implemented features.

## Development and Contributions

Evil Hospice was developed as a university group project by three students at the University of Bari.

- **Guillaume Desaphy** — Primary developer, game design, gameplay implementation, and level design.
- **Mirko Pepe** — Game design, graphic design, and level design.
- **Pietro Conca** — Game design and level design.

The project involved designing gameplay mechanics, implementing game systems in Unity, creating and adapting pixel-art assets, and building the playable level.

## Assets and Credits

The game combines original artwork created for the project with freely available third-party assets, including environmental tiles, interface elements, and audio resources.

Third-party assets remain subject to their respective authors' rights and license conditions.

## Project Context

This repository preserves a university game development project completed during the 2023–2024 academic year and subsequently maintained for portfolio purposes.

The main objective was to gain practical experience in Unity and C#, covering the development process from initial game design and asset creation to gameplay implementation, level construction, and standalone builds.

The repository is maintained primarily as an academic and software development portfolio project.
