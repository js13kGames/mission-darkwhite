---
genres:
  - shooter
  - rpg
  - action
post: https://github.com/cutout-studios/js13k-2026/blob/main/docs/POSTMORTEM.md
video: https://youtu.be/YLJcHYEQne4
# See github.com/js13kGames/hello-world for supported frontmatter
---

> 🚨 System Requirements 🚨
> - [WebGPU Support](https://enablegpu.com/) - only Mac/Windows so far.
> - A keyboard and *two-button* mouse!

# MISSION: DARKWHITE
MISSION: DARKWHITE is a genre experiment that combines rail shooting (e.g. StarFox) with ARPG loot mechanics (e.g. Diablo).

Defeat the waves of incoming enemies. Similarly-colored items in the shape of _your_ ship will drop and float towards you - **keep a sharp eye out and grab them!** 

_These items are key to beating the game_ - you can EQUIP them to power up your ship or use several to RESTORE your character to the full colors of the rainbow!

Also, you may find it tricky to aim - this is an intentional skill for you to master. Firing both weapons at the same time makes it easier!

## Controls

| Input | Action |
| --- | --- |
| Mouse Cursor | Aim weapons |
| `LMB` | Fire left weapon |
| `RMB` | Fire right weapon |
| `WASD` | Strafe Ship |
| `Space` | Deflect bullets |
| `F` | Pause the game and manage your collected items |

### Concepts
- GAS governs everything you do - attacks and spin counters. The heavier (more KG) your ship has, the more expensive things get. You need to wait for your GAS to refill when you run out.
- Each time you run out of HP your REZ is depleted by one. **Zero REZ?** Game Over.
- While paused, you can select the items in your inventory on the left and then "EQUIP" them with the equip button.
- While two or _more_ items are selected, you can also "RESTORE" (i.e. combine) them to randomly generate something more powerful. Gather one ⭐️⭐️ item or higher of each color to complete the mission. 
- [See this table](https://github.com/cutout-studios/js13k-2026#item-effects) for a list of all item modifier explanations.

### Disclaimer
Being my first full digital game, among other resources I used a chatbot to learn the ropes. Also in the final five days of the jam, to get over the finish line. 
