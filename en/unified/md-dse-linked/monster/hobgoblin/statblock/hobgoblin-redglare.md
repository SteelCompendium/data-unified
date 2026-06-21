---
agility: 2
ev: "16"
file_basename: hobgoblin-redglare
file_dpath: monster/hobgoblin/statblock
free_strike: 6
immunities:
    - Fire 6
intuition: 3
item_id: hobgoblin-redglare
item_name: Hobgoblin Redglare
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 6
might: 0
movement: Teleport
name: Hobgoblin Redglare
organization: Platoon
presence: 3
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-redglare
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "70"
type: statblock
---

| Goblin, Hobgoblin, Humanoid, Infernal |            -             |      Level 6      |     Platoon Hexer     |        EV 16         |
|:-------------------------------------:|:------------------------:|:-----------------:|:---------------------:|:--------------------:|
|            **1L**<br>Size             |      **5**<br>Speed      | **70**<br>Stamina |  **4**<br>Stability   | **6**<br>Free Strike |
|        **Fire 6**<br>Immunity         | **Teleport**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **0**<br>Might             |    **+2**<br>Agility     | **+2**<br>Reason  |  **+3**<br>Intuition  |  **+3**<br>Presence  |

> 🏹 **Eye Flash (Signature Ability)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 corruption damage; P < 1 [slowed](../../../condition/slowed.md) (save ends)
> - **12-16:** 14 corruption damage; P < 2 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** 17 corruption damage; P < 3 [restrained](../../../condition/restrained.md) (save ends)

> 🏹 **Glare of the Old Judgments (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Magic, Ranged, Strike** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 corruption damage
> - **12-16:** 10 corruption damage, or if the target has P < 2 they are judged
> - **17+:** The target is judged.
>
> **Effect:** Until the end of the encounter, a judged target takes 10 corruption damage at the start of each of their turns, and regains 5 [Stamina](../../../rule/health/stamina.md) each time they use an ability or other effect that allows another creature to spend a Recovery.

> ⭐️ **Infernal Ichor**
>
> When the redglare is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the redglare takes 3 fire damage.
