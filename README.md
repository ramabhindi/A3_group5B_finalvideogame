# Group 5 A3 — Defend the Hive

## Description

Defend the Hive is a wave based defense game where players protect a beehive from incoming bears, birds, foxes, and hornets. Players earn Honey by defeating enemies and use it to purchase permanent upgrades in the shop. As rounds progress, enemies become more difficult and players must balance resource management, upgrades, quick reactions, and attention to keep the hive alive.

The final version expands the game with multiple interaction mechanics. When a fox appears, it attempts to steal the player's Honey and the player must quickly type "fox" to stop it. A hornet was also added as another enemy mechanic and requires the player to press the Spacebar 10 times to defeat it. Tutorials between rounds explain these mechanics before players encounter them.

## Design Rationale

The game uses clear affordances to help players understand how to interact with the interface. Buttons such as SHOP, Pause, and Start are visually distinct and placed in locations where players expect interactive elements to appear. Keyboard shortcuts were also added for the shop and pause functions to give players faster ways to control the game.

GameFlow principles are supported through clear goals, immediate feedback, gradual progression, and increasing challenge. Players receive visual and audio feedback when damaging enemies, earning Honey, purchasing upgrades, and interacting with special enemies. The difficulty increases across rounds to maintain a balance between accessibility and challenge.

The game was designed around ADHD by encouraging focus through short gameplay loops, immediate feedback, varied interactions, and continuous player involvement. Instead of requiring only one type of interaction, players click regular enemies, type "fox" when a fox appears, and repeatedly press the Spacebar when encountering a hornet. Tutorials between rounds clearly explain new mechanics before they are introduced. Sounds, visual feedback, Honey rewards, upgrades, and increasing difficulty provide frequent feedback and goals throughout the game.

## Setup and Interaction Instructions

To run the sketch locally, open `index.html` in Google Chrome using Live Server.

### Controls

- Click on bears and birds to scare them away.
- When the fox appears, type `fox` to stop it from stealing your Honey.
- When the hornet appears, press Spacebar 10 times to defeat it.
- Click the SHOP button or press S to open the shop.
- Click the Pause button or press P to pause and resume the game.
- Press Spacebar to start the game.
- Press Enter to begin the next round.
- Follow the tutorial instructions between rounds when a new enemy mechanic is introduced.

Protect the hive from enemies before they reach and damage it. Earn Honey by defeating enemies and spend it in the shop on permanent upgrades that help you survive increasingly difficult rounds.

### Opening the Chrome Console

- **Windows:** Press `F12` or `Ctrl + Shift + J`, then click the **Console** tab.
- **Mac:** Press `Cmd + Option + J`.

## Features Added for the Final Game

- Added smoother enemy movement and improved gameplay transitions.
- Added a fox enemy that attempts to steal the player's Honey.
- Added a typing mechanic that requires the player to type "fox" to stop the fox.
- Added a tutorial between rounds explaining how to defend against the fox.
- Added a hornet as a third gameplay mechanic.
- Added a hornet interaction requiring the player to press the Spacebar 10 times to defeat it.
- Added a tutorial explaining the hornet mechanic before it is introduced.
- Added S and P keyboard shortcuts for the shop and pause controls.
- Improved the visibility and readability of interface text.
- Added additional sound effects for the fox and hornet.
- Fixed an issue where birds could damage the hive while the game was paused.
- Fixed a turret related gameplay issue.
- Fixed bear and bird sound behaviour when projectiles hit enemies.
- Adjusted the Bee Swarm upgrade price for better game balance.
- Refined difficulty progression to make later rounds more challenging.
- Continued using short gameplay loops, immediate feedback, and varied interactions to support players with ADHD.

## Iteration Notes

### Post Playtest Changes

1. Improved UI readability by adjusting text visibility and making important interface information easier to identify.

2. Refined the visual presentation and gameplay feedback based on observations from playtesting.

3. Adjusted difficulty balancing so the opening rounds progress more quickly and later rounds provide a stronger challenge.

4. Added clearer instructions for special enemy interactions after playtesters showed confusion about how to stop the fox.

### Post Showcase Changes

1. Added keyboard shortcuts for the shop and pause controls to make these actions faster and easier to access.

2. Added tutorials between rounds so players learn how to defend against the fox and hornet before encountering each mechanic.

3. Added the hornet as a third gameplay mechanic. The player must press the Spacebar 10 times to defeat it, creating another form of interaction beyond clicking enemies and typing.

4. Fixed the issue that allowed birds to damage the hive while the game was paused.

5. Added sound effects for the fox and hornet and corrected sound behaviour for existing enemies.

6. Fixed the turret issue and continued adjusting gameplay systems for a smoother experience.

7. Increased the Bee Swarm upgrade price and continued balancing difficulty and progression across rounds.

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