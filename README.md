# Group 5 A3 — Defend the Hive

## Description

Defend the Hive is a wave based defense game where players protect a beehive from incoming bears, birds, and a fox. Players earn Honey by defeating enemies and use it to purchase permanent upgrades in the shop. As rounds progress, enemies become more difficult and players must balance resource management, upgrades, quick reactions, and attention to keep the hive alive.

The final version improves the movement and visual presentation of the game while introducing a new fox mechanic. When the fox appears, it attempts to steal the player’s Honey. The player must quickly type `fox` to stop it before Honey is lost. This creates a new challenge that requires players to respond in a different way than simply clicking enemies.

## Design Rationale

The game uses clear affordances to help players understand how to interact with the interface. Buttons such as **SHOP**, **Pause**, and **Start** are visually distinct and placed in locations where players expect interactive elements to appear. Enemy movement toward the hive also communicates the player’s objective without requiring extensive instructions. Players quickly learn that clicking enemies protects the hive and earns rewards.

GameFlow principles are supported through clear goals, immediate feedback, gradual progression, and increasing challenge. Players receive visual and audio feedback when damaging enemies, earning Honey, purchasing upgrades, advancing through rounds, and successfully stopping the fox. The increasing challenge keeps players engaged while maintaining a balance between difficulty and player skill.

The game was designed around ADHD by encouraging focus through short gameplay loops, immediate rewards, and continuous interaction. Players receive constant feedback through sounds, visual effects, Honey rewards, upgrade purchases, and enemy reactions. The fox typing mechanic introduces a brief attention based challenge that requires the player to quickly shift focus and respond. The upgrade system provides frequent goals and a sense of progression, while the simple click based controls reduce cognitive load and allow players to focus on the core gameplay experience. Clear objectives, quick feedback, accessible controls, and smoother movement were intentionally used to create an engaging experience for players with ADHD.

## Setup and Interaction Instructions

To run the sketch locally, open `index.html` in Google Chrome using Live Server.

### Controls

- Click on bears and birds to scare them away.
- When the fox appears, type `fox` to stop it from stealing your Honey.
- Click the **SHOP** button to purchase upgrades.
- Press **Spacebar** to start the game.
- Press **Enter** to begin the next round.
- Click the **Pause** button to pause and resume the game.

Protect the hive from enemies before they reach and damage it. Earn Honey by clicking enemies and spend it in the shop on permanent upgrades that help you survive increasingly difficult rounds.

### Opening the Chrome Console

- **Windows:** Press `F12` or `Ctrl + Shift + J`, then click the **Console** tab.
- **Mac:** Press `Cmd + Option + J`.

## Features Added for the Final Game

- Added smoother enemy movement and improved gameplay transitions.
- Added a fox enemy that attempts to steal the player’s Honey.
- Added a typing mechanic that requires the player to type `fox` to stop the fox.
- Improved visual readability and overall interface presentation.
- Refined difficulty progression across rounds.
- Improved feedback for enemy interactions, purchases, and achievements.
- Maintained the shop and permanent upgrade system from the previous version.
- Continued using short gameplay loops and immediate feedback to support players with ADHD.

## Iteration Notes

### Post Playtest Changes

1. Improved UI readability by adjusting text visibility and adding outlines to important interface elements such as the Honey counter.

2. Refined the visual design by updating fonts and improving the overall bee themed presentation.

3. Adjusted difficulty balancing to create a smoother progression between rounds and improve the overall gameplay experience.

### Post Showcase Changes

1. Improved the movement and animation of game elements to create a smoother and more polished experience.

2. Added a fox enemy as a new gameplay mechanic instead of adding a traditional boss fight. The fox attempts to steal the player’s Honey, and the player must type `fox` to stop it.

3. Added a different form of interaction through the fox typing challenge, creating more gameplay variety beyond clicking bears and birds.

4. Continued refining the pacing and difficulty of the game so that the challenge increases more smoothly across rounds.

## Assets

|                 File                      |              Source                    |
----------------------------------------------------------------------------------------------- |
| `assets/images/happy_bee.png` [1] | *Chillin by the Beehive* — Adobe Firefly Image Generation |
| `assets/images/bear.png` [2] | *Cute Big Bear Sprite Sheet* — OpenGameArt |
| `assets/images/bird.png` [3] | *Bird Sprite* — NicePNG |
| `assets/images/fox_sprite.png` [4] | Fox sprite — Alisa Christopher |
| `assets/sounds/bear_growl.wav` [5] | Sound Spark — *Creatures: Beast, Grunt, Growl, Deep* |
| `assets/sounds/button_click.wav` [6] | Artlist Foley — *Switches and Buttons: Tiny Button, Pressing, Click* |
| `assets/sounds/bird_squak.wav` [7] | Sonic Bat — *Birdwatching: Trichoglossus Moluccanus Parrot, Single Throaty Chirp* |
| `assets/sounds/hive_damage.wav` [8] | Soundtrack Creation — *Knights & Weapons: Arrow Hitting Wood, Thud, Crack* |
| `assets/sounds/bees_buzzing.wav` [9] | Craig Carter Collection — *Insects: Bees Flying Around, Background Bee Hive Buzz* |
| `assets/sounds/turret_shot.wav` [10] | Front Row SFX by Pole Position — *Battle Rifles: Heckler & Koch G3, Gun Firing, Single Shot, Far* |
| `assets/sounds/purchase.wav` [11] | Matching Sound Effects — *Coins: Dropping a Few Coins on Other Coins* |
| `assets/sounds/decline.wav` [12] | Krotos — *Small Office: Button, Elevator, Beep, Bright* |
| `assets/sounds/achievement.wav` [13] | Ni Sound — *Funny Game: Rolling Tones, Positive Achievement* |
| `assets/sounds/background_music.mp3` [14] | Solis — *Sneaky Business* |

## References

[1] Adobe Firefly. n.d. *Chillin by the Beehive*. Adobe Firefly Image Generation.

[2] OpenGameArt. n.d. *Cute Big Bear Sprite Sheet*. Retrieved July 13, 2026, from  
https://opengameart.org/content/cute-big-bear

[3] NicePNG. n.d. *Bird Sprite*. Retrieved July 13, 2026, from  
https://www.nicepng.com/maxp/u2q8q8i1q8w7r5i1/

[4] Christopher, Alisa. 2007. *Monster018 Fox*. Retrieved from  
https://alisachristopher.wordpress.com/2007/10/05/aveyond-ii/monster018-fox/

[5] Sound Spark. n.d. *Creatures — Beast, Grunt, Growl, Deep*. Artlist.

[6] Artlist Foley. n.d. *Switches and Buttons — Tiny Button, Pressing, Click*. Artlist.

[7] Sonic Bat. n.d. *Birdwatching — Trichoglossus Moluccanus Parrot, Single Throaty Chirp*. Artlist.

[8] Soundtrack Creation. n.d. *Knights & Weapons — Arrow Hitting Wood, Thud, Crack*. Artlist.

[9] Craig Carter Collection. n.d. *Insects — Bees Flying Around, Background Bee Hive Buzz*. Artlist.

[10] Front Row SFX by Pole Position. n.d. *Battle Rifles — Heckler & Koch G3, Gun Firing, Single Shot, Far*. Artlist.

[11] Matching Sound Effects. n.d. *Coins — Dropping a Few Coins on Other Coins*. Artlist.

[12] Krotos. n.d. *Small Office — Button, Elevator, Beep, Bright*. Artlist.

[13] Ni Sound. n.d. *Funny Game — Rolling Tones, Positive Achievement*. Artlist.

[14] Solis. n.d. *Sneaky Business*. Artlist.