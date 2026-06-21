---
agility: 2
ev: "10"
file_basename: wode-elf-gweiadur
file_dpath: monster/elf-wode/statblock
free_strike: 5
intuition: 1
item_id: wode-elf-gweiadur
item_name: Wode Elf Gweiadur
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
might: 0
movement: Climb
name: Wode Elf Gweiadur
organization: Platoon
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-gweiadur
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "40"
type: statblock
---

| Fey, Humanoid, Wode Elf |           -           |      Level 3      |   Platoon Artillery   |        EV 10         |
|:-----------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size      |    **7**<br>Speed     | **40**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|    **-**<br>Immunity    | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|     **0**<br>Might      |   **+2**<br>Agility   |  **0**<br>Reason  |  **+1**<br>Intuition  |  **0**<br>Presence   |

> 🏹 **Snare Bow (Signature Ability)**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 15**           | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage
> - **17+:** 14 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** The gweiadur [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** If this ability [restrains](scc.v1:mcdm.heroes.v1/condition/restrained) the target, one enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target is also [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).

> 🔳 **You Activated My Trap! (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic, Ranged** |                  **Maneuver** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage; R < 0 the target is marked (save ends)
> - **12-16:** 6 damage; R < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and the target is marked (save ends)
> - **17+:** 9 damage; R < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and the target is marked (save ends)
>
> **Effect:** Allies gain an edge on abilities against a target marked by any wode elf.

> ⭐️ **Masking Glamor**
>
> Abilities targeting the gweiadur that would take a bane from cover or concealment have a double bane instead.
