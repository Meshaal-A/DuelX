

# DuelX

**DuelX** is an engaging two-player fighting game built with Python and Pygame. This project features exciting gameplay mechanics, unique characters, and dynamic animations, making it a perfect choice for retro game enthusiasts and developers interested in Python-based game development.

## Features
### **Two Distinct Fighters**
- **Warrior**: A skilled melee combatant with powerful sword-based attacks. The Warrior excels in close-range combat with fast and devastating strikes. 
- **Wizard**: A magical fighter capable of casting powerful spells. The Wizard has the advantage of long-range attacks, using fireballs and other spells to damage the opponent from a distance.

### **Gameplay Mechanics**
- **Health Bars**: Each fighter has a health bar that decreases when they are hit. The first player to reduce the opponent's health to zero wins the round.
- **Smooth Animations**: Each fighter has animations for different actions including idle, running, jumping, attacking, getting hit, and dying.
- **Scoring System**: The game tracks the number of rounds won by each player. The player with the most rounds wins the match.

### **Dynamic Background**
- The background changes with each level and features blur effects during the main menu for an immersive cinematic experience.

### **Sound Effects and Music**
- **Background Music**: Engaging soundtracks are used for each level.
- **Attack Effects**: Impact sounds and special effect sounds are played when an attack lands or a spell is cast.

### **Responsive UI**
- **Main Menu**: The main menu includes options for starting the game, checking the score, and exiting the game.
- **Victory Screen**: After each match, a victory screen shows the winning fighter and the number of rounds won.

### **Custom Controls for Two Players**
- The game is designed for two players, each controlling a fighter using custom controls for movement, jumping, and attacking.

### **Level Progression**
- The game progresses through multiple levels, each with its own challenges and difficulty:
  - **Level 1**: The initial level where players learn the basic mechanics of the game. The enemies are relatively easy to defeat.
  - **Level 2**: A harder level where enemies are faster, stronger, and use advanced tactics.
  - **Level 3**: The final showdown, where the player faces the hardest opponent with enhanced abilities, including faster attacks and better defensive strategies.

### **Screen Transitions**
- **Smooth Fade Effects**: When transitioning between rounds or levels, fade effects are applied to give the game a cinematic flow. This includes transitions between levels and after each round.

### **Game Reset and Countdown**
- After each round, the game automatically resets the fighters and a countdown is displayed before the next round begins. This countdown creates suspense and prepares the players for the next fight.

### **Additional Features**
- **Combo System**: Players can chain attacks together to create powerful combos that deal more damage. The combo system rewards skill and timing.
- **Special Abilities**: Each fighter has a unique special ability that can be activated after a certain threshold of damage is dealt. The Warrior can perform a powerful sword slash, while the Wizard can unleash a destructive magic spell.

## 📋 Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Gameplay Instructions](#gameplay-instructions)
- [Downloads](#downloads)
- [License](#license)
- [Credits](#credits)
- [Contributing](#contributing)
- [Contact](#contact)

## Requirements
- Python 3.7 or higher
- Required Python libraries:
  - `pygame`
  - `numpy`
  - `opencv-python`

## Installation

Follow these steps to install and run the game:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Meshaal-A/DuelX.git
   cd DuelX
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Game**:
   ```bash
   python src/main.py
   ```

## Gameplay Instructions

### Player Controls:
- **Player 1**:
  - Move: `A` (Left), `D` (Right)
  - Jump: `W`
  - Attack: `R` (Attack 1), `T` (Attack 2)

- **Player 2**:
  - Move: Left Arrow (`←`), Right Arrow (`→`)
  - Jump: Up Arrow (`↑`)
  - Attack: `M` (Attack 1), `N` (Attack 2)

### Objective:
- The goal is to reduce your opponent's health to zero to win the round. The game includes multiple rounds, and the first player to win the majority of rounds wins the match. Victory is celebrated with a dynamic win screen!

## Downloads
You can download the latest release of **DuelX** from the following link:

[![Version](https://img.shields.io/github/v/release/Meshaal-A/DuelX?color=%230567ff&label=Latest%20Release&style=for-the-badge)](https://github.com/Meshaal-A/DuelX/releases/latest) 

[![Download](https://custom-icon-badges.demolab.com/badge/-Download-0B6623?style=for-the-badge&logo=download&logoColor=white)](https://github.com/Meshaal-A/DuelX/releases/download/v1.1/Game.zip)


## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it in your projects.

## Credits

- **Assets**:
  - Background music and sound effects: [Free Music Archive](https://freemusicarchive.org/)
  - Fonts: [Turok Font](https://www.fontspace.com/turok-font)
  - Sprites: Custom-designed and modified from open-source assets.

## Contributing

Contributions are welcome! Here's how you can help:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add YourFeatureName"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Open a pull request.

Check the [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## Contact

If you have any questions or need further assistance, reach out to the maintainer:
- **Developer**: Meshaal A
- **Email**: [mishalayubkhan10@gmail.com](mailto:mishalayubkhan10@gmail.com)
```

### Key Updates:
- Expanded features, including detailed descriptions for each level and game mechanics.
- Special abilities and combo system added to increase the depth of gameplay.
- Clear instructions for contributing and additional installation steps.

This version gives a more comprehensive view of your project and its functionalities. Let me know if you'd like further updates or changes!
