# 3D Battle On Earth

A third-person 3D fighting game featuring combat mechanics, enemy AI, and arena-based gameplay.

## Description

3D Brawler Arena is a third-person fighting game where players navigate through a city, facing off against various enemies including regular AI opponents and a challenging boss. The game features a comprehensive fighting system with multiple combat stances, combo attacks, and special moves. Players must master both movement and combat mechanics to survive waves of enemies in an urban arena environment.

## Screenshots

## Screenshots

![Screenshot 1](screenshots/screenshot1.png)
Main menu

![Screenshot 2](screenshots/screenshot2.png)
Controls menu

![Screenshot 3](screenshots/screenshot3.png)
Volume control in options

![Screenshot 4](screenshots/screenshot4.png)
Third person camera and movement

![Screenshot 5](screenshots/screenshot5.png)
Fighting enemy

![Screenshot 6](screenshots/screenshot6.png)
Fighting enemy but blocking

![Screenshot 7](screenshots/screenshot7.png)
Approaching boss

## Features

- *Third-Person Combat System* - Melee fighting with three attack combinations
- *Dynamic Fighting Stances* - Switch between punch and kick combat modes
- *Enemy AI System* - Enemies detect and chase players within range
- *Boss Battle* - Final boss with projectile attacks and aggressive AI
- *Special Moves* - Dodge rolls, combo attacks, and special techniques
- *Health System* - Player and enemy health management
- *Urban Arena Map* - Detailed 3D environment with strategic barriers
- *Audio Integration* - Background music and sound effects with volume control

## Requirements

### To Play:
- *Platform:* Windows 10/11, macOS 10.15+, or Linux Ubuntu 18.04+
- *Memory:* 4 GB RAM minimum
- *Graphics:* DirectX 11 compatible
- *Storage:* 2 GB available space

### To Develop:
- *Unity Version:* 2022.3.x LTS or higher
- *Platform:* Windows/macOS/Linux
- *Required Packages:*
  - TextMeshPro
  - Universal Render Pipeline (URP)
  - Input System

## Installation

### For Players:
1. Download the latest release from [Releases](https://minn01.itch.io/battle-on-earth)
2. Extract the zip file
3. Run the executable file
4. Enjoy!

### For Developers:
1. Check out the google cloud link in this link : [itch.io](https://minn01.itch.io/battle-on-earth) 
2. Open Unity Hub
3. Click "Open" and select the project folder
4. Wait for Unity to import all assets
5. Open the main scene: Assets/Scenes/MenuScene.unity
6. Press Play to test

## How to Play

1. *Navigation*: Use WASD keys to move around the arena. The camera will follow your character in third-person view.

2. *Combat Preparation*: Press *E* to enter fighting stance when enemies are nearby. Your character will assume a combat-ready position.

3. *Basic Combat*: 
   - Use *Left Click* to perform punch combinations
   - Press *Q* to switch between Punch Mode and Kick Mode
   - Each mode has its own unique 3-hit combo sequence
   - Use right click to block

4. *Advanced Combat*:
   - Master dodge rolling by double-tapping movement keys while in fighting stance
   - Use special moves (R, F, C) for powerful attacks
   - Monitor your health bar during combat

5. *Enemy Engagement*:
   - Regular enemies will chase you when you get within their detection range
   - The boss enemy shoots projectiles and has aggressive AI behavior
   - Boss health bar appears when you enter the boss arena

6. *Survival*: Navigate the city using barriers and spacing to your advantage while engaging multiple enemies.

## Controls

### Basic Movement:
- *WASD* - Move forward, backward, left, and right
- *Mouse* - Third-person camera control

### Combat System:
- *E* - Enter/Exit fighting stance
- *Left Click* - Execute punch combo (in fighting stance)
  - 1st: Left Jab
  - 2nd: Right Uppercut  
  - 3rd: Right Hook
- *Right Click* - Block 
- *Q* - Toggle between Punch Mode and Kick Mode (in fighting stance)

### Kick Combo (when in Kick Mode):
- *Left Click* - Execute kick combo
  - 1st: Knee Lead
  - 2nd: Right Push Kick
  - 3rd: Right Kick Classic

### Dodging (in fighting stance):
- *W + W* (double tap) - Forward dodge roll
- *S + S* (double tap) - Backward step dodge

### Special Moves:
- *R* - Quick Punch Combo
- *F* - Front Flip Kick  
- *C* - Flying Kick

### Menu:
- *Title Screen*
- *Volume Controls* - Adjust music volume in settings

## Development

### Key Scripts:
- PlayerController.cs - Handles player movement and input
- ComboSystem.cs - Manages combat mechanics and stance switching  
- EnemyAI.cs - Controls enemy detection, chasing, and combat behavior

### Building:
1. Go to File → Build Settings
2. Select your target platform
3. Click "Build" and choose output folder
4. Test the build before distribution

## Assets & Credits

### Third-Party Assets:

*Unity Asset Store:*
- *Brawler Animations - Free* by SainDeveloper
  - Version: 1.0.1
  - Used for: Fighting animations and combat moves
  - License: Standard Unity Asset Store EULA

- *Demo City* by Versatile Studio (Mobile Friendly)  
  - Version: 1.0
  - Used for: Urban arena environment and map assets
  - License: Standard Unity Asset Store EULA

*External Resources:*
- *Character Model & Movement* - [Characters3D.com](https://characters3d.com)
  - Used for: Player character model and basic movement animations

- *Additional Fight Animations* - Maximo
  - Used for: Extended combat animation sequences

### Development Team:
- *[Min Thant]* - Player and regular enemy animations and control
- *[Thant Zin Min]* - Menu Interface and Map Design
- *[Si Thu Naung]* - Boss Combat System and hitbox collision systems and animations

## License

MIT License

Copyright (c) 2025 [Min Thant]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

*Asset Licenses:*
- Unity Asset Store assets used under Standard Unity Asset Store EULA
- Characters3D.com assets used under their respective licensing terms
- Maximo animations used under applicable license agreement
---
