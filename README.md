# Jumpa
Small platformer game from a challenge using Pygame Zero. Get the flags while avoid the thorns and the flying ghosts.

<img width="514" height="514" alt="jumpa-menu" src="https://github.com/user-attachments/assets/8f7d344a-f038-4c3c-9fdf-4c589b587001" />

### Requirements of the challenge
1. The ONLY libraries allowed are pgzero, math and random;
2. The game have to be either a roguelike, a point-and-click adventure or a platformer;
3. A main menu is needed with the following buttons: Play game, Turn music on/off, Exit;
4. The game have to play a background music and have some sound effects; 
5. The game need enemies that are dangerous to the "hero";
6. Such enemies move within it's own path in the levels;
7. Some classes to make the player move and to animate the sprites are required;
8. The "hero" and the enemies need a sprite animation;
9. The name of variables, classes, functions need to follow the [PEP8](https://peps.python.org/pep-0008/);
10. The game can't have really obvious bugs.
11. All make in one file and made from scratch (without templates or help from another person).

### How to play
You'll need to have [Python](https://www.python.org/downloads/) installed in your machine.

You'll also need to download [Pygame Zero](https://pygame-zero.readthedocs.io/en/stable/) by typing in your terminal:
```
pip install pgzero
```
Go to this project file then type:
```
pgzrun main.py
```
The controls:
- ```A```: move left
- ```D```: move right
- ```Space```: jump
- ```K```: go back to previous level
- ```L```: advance to next level

### Modify it!
I tried to build the game systems in a way that is easy to change the values, change the maps, even making new levels if you want.
The map is just a string of characters, what means you can build your own by coping those that are already in the code and changing as much as you want!

<img width="514" height="514" alt="jumpa-lvl" src="https://github.com/user-attachments/assets/8a74b6ab-e355-40da-820d-20b1002edbf1" />

### References, inspirations and credits
- Music: [Call Me, Homie - Clement Panchout](https://clement-panchout.itch.io/yet-another-free-music-pack)
- Hit sound effect: [Retro Sounds - artisticdude](https://opengameart.org/content/retro-sounds-0)
- Flag sound effect: [Space Shooter - dravenx](https://opengameart.org/content/space-shooter-sound-effects)
- All sprites was made by me, but I want to give some credit to [Pixelnauta, the author of this tileset](https://pixelnauta.itch.io/slime-pixel-32x32?download) that inspired me.
