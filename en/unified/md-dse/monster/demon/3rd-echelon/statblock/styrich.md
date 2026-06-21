---
agility: 4
ev: "10"
file_basename: styrich
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 3
intuition: 2
item_id: styrich
item_name: Styrich
keywords:
    - Abyssal
    - Demon
level: 8
might: 2
name: Styrich
organization: Horde
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/styrich
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 1
stamina: "45"
type: statblock
weaknesses:
    - Holy 5
---

|  Abyssal, Demon   |         -         |      Level 8      |     Horde Hexer      |          EV 10           |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:------------------------:|
|  **1L**<br>Size   |  **6**<br>Speed   | **45**<br>Stamina |  **1**<br>Stability   |   **3**<br>Free Strike   |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **Holy 5**<br>Weakness  |
|  **+2**<br>Might  | **+4**<br>Agility | **+0**<br>Reason  |  **+2**<br>Intuition  |    **+0**<br>Presence    |

> 🗡 **Hair Whip (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 4**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; pull 1
> - **12-16:** 10 damage; pull 2, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 12 damage; pull 3, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** Any target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by the styrich's Tangled Nest ability can be pulled the distance determined by the power roll.

> ❇️ **Tangled Nest (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**       |                  **Maneuver** |
> |----------------|------------------------------:|
> | **📏 4 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** A < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** [Slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT) or A < 3 3 damage and [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
> - **17+:** [Restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT) or A < 4 3 damage and [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)

> ⭐️ **Lethe**
>
> While the styrich is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.

> ⭐️ **Soulsight**
>
> Any creature within 2 squares of the styrich can't be hidden from them.
