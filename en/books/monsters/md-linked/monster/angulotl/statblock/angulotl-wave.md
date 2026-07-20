---
agility: 0
ev: "3"
free_strike: 1
immunities:
    - Poison 2
intuition: 2
keywords:
    - Angulotl
    - Humanoid
level: 1
might: 0
movement: Climb, swim
name: Angulotl Wave
organization: Horde
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-wave
size: 1S
speed: 5
stability: 0
stamina: "10"
type: statblock
---

|    Angulotl, Humanoid    |              -              |      Level 1      |   Horde Controller    |         EV 3         |
|:------------------------:|:---------------------------:|:-----------------:|:---------------------:|:--------------------:|
|      **1S**<br>Size      |       **5**<br>Speed        | **10**<br>Stamina |  **0**<br>Stability   | **1**<br>Free Strike |
| **Poison 2**<br>Immunity | **Climb, swim**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|     **+0**<br>Might      |      **+0**<br>Agility      | **+0**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> 🏹 **Refulgent Beams (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------------------:|
> | **📏 Ranged 8**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 holy damage
> - **12-16:** 4 holy damage; R < 1 the target is illuminated (save ends)
> - **17+:** 5 holy damage; R < 2 the target is illuminated (save ends)
>
> **Effect:** An illuminated creature or object can't hide or become invisible, and any strike made against an illuminated target gains an [edge](../../../rule/dice/edge.md).

> 🔳 **Noxious Bubble (2 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Magic, Ranged**                     | **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------------------------|----------------:|
> | **📏 2 cube of unoccupied space within 10** |  **🎯 Special** |
>
> **Effect:** A bubble of toxic gas fills the area, ready to pop. If any creature or object touches the bubble or if the bubble takes damage, it bursts. Each angulotl adjacent to the bubble is wet until the end of the encounter, and each enemy adjacent to the bubble makes a **[Might](../../../rule/character/might.md) test**.
>
> - **≤11:** 3 poison damage; the target is wet and [weakened](../../../condition/weakened.md) (save ends)
> - **12-16:** 2 poison damage; the target is wet (save ends)
> - **17+:** 1 poison damage; the target is wet ([EoT](../../../rule/combat/end-of-turn.md))

> ⭐️ **Toxiferous**
>
> Whenever an adjacent enemy [grabs](../../../feature/common/maneuvers/grab.md) the wave or uses a melee ability against them, that enemy takes 2 poison damage.
