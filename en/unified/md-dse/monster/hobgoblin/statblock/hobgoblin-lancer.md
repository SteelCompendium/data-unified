---
agility: 3
ev: 6 for four minions
file_basename: hobgoblin-lancer
file_dpath: monster/hobgoblin/statblock
free_strike: 2
immunities:
    - Fire 2
intuition: 2
item_id: hobgoblin-lancer
item_name: Hobgoblin Lancer
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 1
name: Hobgoblin Lancer
organization: Minion
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-lancer
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "8"
type: statblock
with_captain: +2 damage bonus to strikes
---

| Goblin, Hobgoblin, Humanoid, Infernal |         -         |     Level 4      |                 Minion Harrier                 | EV 6 for four minions |
|:-------------------------------------:|:-----------------:|:----------------:|:----------------------------------------------:|:---------------------:|
|            **1M**<br>Size             |  **7**<br>Speed   | **8**<br>Stamina |               **0**<br>Stability               | **2**<br>Free Strike  |
|        **Fire 2**<br>Immunity         | **-**<br>Movement |        -         | **+2 damage bonus to strikes**<br>With Captain |   **-**<br>Weakness   |
|            **+1**<br>Might            | **+3**<br>Agility | **0**<br>Reason  |              **+2**<br>Intuition               |   **0**<br>Presence   |

> ⚔️ **Grim Thrust (Signature Ability)**
>
> | **Magic, Melee, Ranged, Strike, Weapon** |                          **Main action** |
> |------------------------------------------|-----------------------------------------:|
> | **📏 Melee 2 or ranged 5**               | **🎯 One creature or object per minion** |
>
> **Power Roll + 3:**
>
> - **≤11:** 2 corruption damage
> - **12-16:** 4 corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **17+:** 6 corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
>
> **Effect:** The lancer deals an extra 2 damage if they have high ground against the target.

> ⭐️ **Infernal Ichor**
>
> When the lancer is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they spray burning blood. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the lancer takes 2 fire damage.
