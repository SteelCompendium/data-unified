---
agility: 0
ev: "8"
file_basename: high-elf-deathtouch
file_dpath: monster/elf-high/statblock
free_strike: 5
intuition: 0
item_id: high-elf-deathtouch
item_name: High Elf Deathtouch
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 2
might: 2
name: High Elf Deathtouch
organization: Platoon
presence: 1
reason: 1
role: Artillery
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-deathtouch
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

| Fey, High Elf, Humanoid |         -         |      Level 2      |   Platoon Artillery   |         EV 8         |
|:-----------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size      |  **5**<br>Speed   | **30**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|    **-**<br>Immunity    | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|     **+2**<br>Might     | **0**<br>Agility  | **+1**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence  |

> 🏹 **Heartpiercer (Signature Ability)**
>
> | **Ranged, Strike, Weapon** |     **Main action** |
> |----------------------------|--------------------:|
> | **📏 Ranged 15**           | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 10 damage
> - **17+:** 13 damage; R < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends); P < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The ability takes the Area keyword and loses the Strike keyword, its distance becomes a 3 cube within 10, and it targets each enemy in the area.

> 🗡 **Kiss of Death**
>
> | **Magic, Melee** |            **Maneuver** |
> |------------------|------------------------:|
> | **📏 Melee 1**   | **🎯 One willing ally** |
>
> **Effect:** The target has a +5 bonus to speed and automatically obtains a tier 3 outcome on power rolls. They can still roll to determine if they score a critical hit. At the end of their next turn, the target immediately dies.

> ⭐️ **Otherworldly Grace**
>
> At the start of each of their turns, the deathtouch can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
