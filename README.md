# 3D Horror FPS

A first-person 3D horror game built in Unity, in the style of games like Resident Evil. It is my first 3D game, made as part of an introductory game development course.

**Play it on itch.io:** [Project C](https://darthadox.itch.io/project-c)

## Gameplay

Explore a house, find keys and items, solve puzzles, and escape while being stalked. Items you pick up are kept in an inventory that you can open and use at any time.

## What I Made

The game uses Asset Store packages (see Credits), but the following parts are my own work:

- **Level design:** I built a custom mansion layout from the Horror Mansion assets, including the puzzle flow from the first key to the escape.
- **Stalker AI:** I set up the NavMesh that the stalker uses to move around and chase the player.
- **Audio design:** I designed the soundscape myself, choosing and placing sounds and music from the audio packs to build tension.
- **Asset integration:** I edited scripts to make the Horror Mansion assets work with the horror game kit's systems, so the environment, interactions, and inventory function together.
- **Story:** I wrote a short, deliberately ambiguous story that is told through the notes and events in the game.

## Controls

| Key | Action |
|---|---|
| `W` `A` `S` `D` | Move around |
| `Shift` | Sprint |
| `Ctrl` | Toggle crouch |
| `E` | Interact |
| `Tab` | Open inventory |
| Mouse click | Use items in the inventory |

## Walkthrough

Spoilers below. Read only if you cannot figure out the level on your own.

<details>
<summary>Show walkthrough</summary>

1. Enter the house
2. Get the bathroom key from the living area
3. Open the bathroom
4. Read the note and start the stalker sequence
5. Go to the bedroom
6. Get the bedroom key
7. Get the lockpicks
8. Lockpick the door leading to the stairs
9. Go to the upper floor
10. Find three fuses
11. Put them in the fusebox
12. Connect the circuit board
13. The bookcase opens a secret area
14. Get the gun and attach the gun flash to it
15. Escape

</details>

## Credits

This game uses the following Unity Asset Store packages, all under the [Standard Unity Asset Store EULA](https://unity.com/legal/as-terms). All rights belong to their creators.

| Asset | Publisher | Used for |
|---|---|---|
| [UHFPS - Ultimate Horror FPS KIT (URP)](https://assetstore.unity.com/packages/templates/systems/uhfps-ultimate-horror-fps-kit-urp-254506) | ThunderWire Studio | Horror FPS framework (player, inventory, interaction) |
| [Horror Mansion](https://assetstore.unity.com/packages/3d/environments/horror-mansion-254104) | Art Equilibrium | House environment and props |
| [Horror Game Essentials](https://assetstore.unity.com/packages/audio/sound-fx/horror-game-essentials-153417) | The Artifact | Sound effects |
| [Footsteps Mini Sound Pack](https://assetstore.unity.com/packages/audio/sound-fx/foley/footsteps-mini-sound-pack-307682) | MGWSoundDesign | Footstep sounds |
| [FREE Horror Ambient Music Pack - DESPERATION](https://assetstore.unity.com/packages/audio/ambient/free-horror-ambient-music-pack-desperation-240918) | KarpoSoundtracks | Ambient music |
| [Horror Chase & Ambience Music](https://assetstore.unity.com/packages/audio/music/horror-chase-ambience-music-210570) | IconicWareStudios | Chase and ambience music |
