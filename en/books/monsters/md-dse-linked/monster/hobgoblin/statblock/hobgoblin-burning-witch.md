---
agility: 1
ev: "12"
file_basename: hobgoblin-burning-witch
file_dpath: monster/hobgoblin/statblock
free_strike: 5
immunities:
    - Fire 4
intuition: 2
item_id: hobgoblin-burning-witch
item_name: Hobgoblin Burning Witch
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 0
movement: Teleport
name: Hobgoblin Burning Witch
organization: Platoon
presence: 3
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-burning-witch
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "50"
type: statblock
---

| Goblin, Hobgoblin, Humanoid, Infernal |            -             |      Level 4      |  Platoon Controller   |        EV 12         |
|:-------------------------------------:|:------------------------:|:-----------------:|:---------------------:|:--------------------:|
|            **1M**<br>Size             |      **5**<br>Speed      | **50**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|        **Fire 4**<br>Immunity         | **Teleport**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **0**<br>Might             |    **+1**<br>Agility     | **+2**<br>Reason  |  **+2**<br>Intuition  |  **+3**<br>Presence  |

> 🏹 **Soul Burn (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 4 corruption or fire damage
> - **12-16:** 6 corruption or fire damage
> - **17+:** 8 corruption or fire damage
>
> **2 [Malice](../../../rule/monster/malice.md):** Each target who has P < 2 is [weakened](../../../condition/weakened.md) (save ends). Any enemy who starts their turn within 3 squares of a target [weakened](../../../condition/weakened.md) this way and who has P < 2 is [weakened](../../../condition/weakened.md) (save ends).

> 🏹 **Burning Legion (1 [Malice](../../../rule/monster/malice.md))**
>
> | **Magic, Ranged** |           **Maneuver** |
> |-------------------|-----------------------:|
> | **📏 Ranged 10**  | **🎯 Three creatures** |
>
> **Effect:** Each target can [teleport](../../../movement/teleport.md) up to 5 squares. Each creature [adjacent](../../../rule/combat/adjacent.md) to a target at their destination takes 3 fire damage.

> ⭐️ **Infernal Ichor**
>
> When the burning witch is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the burning witch takes 3 fire damage.
