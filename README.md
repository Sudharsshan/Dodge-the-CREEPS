# Dodge the Creeps

A simple 2D game tutorial project built with the Godot Engine. In this game, you control a character that must avoid enemies (creeps) while collecting points. This is based on the official Godot "Dodge the Creeps" tutorial.

## Prerequisites

- **Godot Engine 4.6** or later
- **Operating System**: Linux (Ubuntu) on Raspberry Pi 5
- Basic knowledge of GDScript (optional, as this is a tutorial)

### Installing Godot on Ubuntu (Raspberry Pi 5)

1. Download the Linux (x86_64) version of Godot from the [official website](https://godotengine.org/download/linux/).
   - Note: For Raspberry Pi 5, ensure you download the appropriate architecture (ARM64 if available, otherwise x86_64 with compatibility mode).

2. Extract the downloaded archive:
   ```bash
   tar -xf Godot_v4.6-stable_linux.x86_64.tar.xz
   ```

3. Move the executable to a directory in your PATH or create a symlink:
   ```bash
   sudo mv Godot_v4.6-stable_linux.x86_64 /opt/godot
   sudo ln -s /opt/godot/Godot_v4.6-stable_linux.x86_64 /usr/local/bin/godot
   ```

4. Make it executable:
   ```bash
   chmod +x /usr/local/bin/godot
   ```

## Project Setup

1. Clone or download this repository:
   ```bash
   git clone <repository-url>
   cd Dodge-the-CREEPS
   ```

2. Open the project in Godot:
   ```bash
   godot project.godot
   ```

## How to Play

- Use the **WASD** keys or **Arrow keys** to move your character around the screen.
- Avoid the enemies (creeps) that spawn and move towards you.
- The game ends when an enemy touches your character.
- Try to survive as long as possible and achieve a high score!

## Project Structure

```
Dodge-the-CREEPS/
├── project.godot          # Godot project configuration
├── player.gd              # Player character script
├── player.tscn            # Player scene
├── icon.svg               # Project icon
├── art/                   # Game assets
│   ├── playerGrey_*.png   # Player sprite animations
│   ├── enemy*.png         # Enemy sprite animations
│   ├── gameover.wav       # Game over sound effect
│   └── House In a Forest Loop.ogg  # Background music
├── fonts/                 # Game fonts
│   └── Xolonium-Regular.ttf
└── README.md              # This file
```

## Controls

- **Move Right**: D or Right Arrow
- **Move Left**: A or Left Arrow
- **Move Up**: W or Up Arrow
- **Move Down**: S or Down Arrow

## Tutorial Steps

This project follows the official Godot "Dodge the Creeps" tutorial. If you're following along, the steps typically include:

1. Setting up the project
2. Creating the player scene and script
3. Adding enemy scenes and spawning logic
4. Implementing collision detection
5. Adding a HUD for score and game over screen
6. Adding sound effects and music
7. Polishing the game

For the complete tutorial, visit the [Godot Documentation](https://docs.godotengine.org/en/stable/getting_started/introduction/index.html).

## Building and Exporting

To export the game for different platforms:

1. In Godot, go to **Project > Export**
2. Add presets for your desired platforms (e.g., Linux, Windows, HTML5)
3. Configure export settings
4. Click **Export Project** and choose a location

For Raspberry Pi 5, you can export as a Linux binary and run it directly.

## Contributing

This is a tutorial project. If you find issues or want to improve it, feel free to submit pull requests or open issues.

## License

This project uses assets from the Godot tutorial, which are licensed under the Creative Commons Attribution 3.0 Unported License. See the [Godot website](https://godotengine.org/license/) for more information.

## Credits

- **Godot Engine**: The game engine used
- **Tutorial**: Based on the official Godot "Dodge the Creeps" tutorial
- **Assets**: Provided by the Godot team and contributors
