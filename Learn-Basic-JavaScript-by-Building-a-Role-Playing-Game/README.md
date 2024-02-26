# Dragon Repeller RPG

Welcome to Dragon Repeller, a simple text-based RPG where you embark on a quest to defeat the dragon that threatens the town. This guide provides an overview of the game's logic and instructions on how to play.

<img width="540" alt="cave" src="https://github.com/Kaisama/FCC-JS-and-Data-Structure-Beta-/assets/109125241/43ef338b-85a4-443c-9ed0-a88df145220a"><br><hr>

<img width="540" alt="dragon" src="https://github.com/Kaisama/FCC-JS-and-Data-Structure-Beta-/assets/109125241/7a2bce4a-d443-4a12-84c1-b43d2cac2464"><br><hr>

<img width="540" alt="store" src="https://github.com/Kaisama/FCC-JS-and-Data-Structure-Beta-/assets/109125241/5570148c-320e-4b1d-86e1-9ae39cbbe37b"><br><hr>


<img width="540" alt="town" src="https://github.com/Kaisama/FCC-JS-and-Data-Structure-Beta-/assets/109125241/d16c62a4-4e2d-4686-b585-40e4b93ac509"><br><hr>

## Game Overview

Dragon Repeller consists of a town square where you, the player, make decisions by choosing actions through buttons. The main game elements include:

- **Stats:** Keep an eye on your XP, Health, and Gold displayed at the top of the screen.
- **Controls:** Interact with the game by clicking on the buttons to "Go to store," "Go to cave," or "Fight dragon."
- **Monster Stats:** Learn about the dragon's health and name when engaging in a fight.
- **Text Section:** Receive updates and instructions in the text area regarding your current situation.

## Player Stats

- **XP (Experience Points):** Earned during your journey and used to level up.
- **Health:** Your character's health level.
- **Gold:** Currency for purchasing items and weapons.

## Weapons

You start with a "stick" and can buy or sell weapons at the store. Weapons include:
- Stick (Power: 5)
- Dagger (Power: 30)
- Claw Hammer (Power: 50)
- Sword (Power: 100)

## Monsters

Monsters vary in difficulty and include:
- Slime (Level: 2, Health: 15)
- Fanged Beast (Level: 8, Health: 60)
- Dragon (Level: 20, Health: 300)

## Locations

1. **Town Square:** Starting point with options to go to the store, cave, or fight the dragon.
2. **Store:** Purchase health or weapons, and return to the town square.
3. **Cave:** Choose to fight different monsters or return to the town square.
4. **Fight:** Engage in battle with a selected monster.
5. **Kill Monster:** After defeating a monster, gain XP and gold.
6. **Lose:** You die. ☠️
7. **Win:** You defeat the dragon! YOU WIN THE GAME! 🎉
8. **Easter Egg:** Discover a secret game with a chance to win gold.

## Game Logic (app.js)

The logic behind the game is implemented in the `app.js` file. Key functionalities include managing player stats, handling button clicks, battling monsters, and determining the game's outcome.

Feel free to explore and modify the script to customize the game or add new features.

## Getting Started

1. Clone the repository:
   `https://github.com/jaganpofficial/role-play-game.git`
  
2. Open index.html in your preferred web browser.

3. Begin your quest and enjoy the Dragon Repeller RPG!
