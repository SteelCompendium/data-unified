---
agility: 2
ev: "16"
free_strike: 5
intuition: 1
keywords:
    - Beast
    - Griffon
level: 2
might: 2
movement: Fly
name: Griffon
organization: Elite
presence: 2
reason: -1
role: Mount
scc: mcdm.monsters.v1/monster.griffon.statblock/griffon
size: "2"
speed: 9
stability: 2
stamina: "80"
type: statblock
---

|  Beast, Griffon   |          -          |      Level 2      |      Elite Mount      |        EV 16         |
|:-----------------:|:-------------------:|:-----------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |   **9**<br>Speed    | **80**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **Fly**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  |  **+2**<br>Agility  | **-1**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Claw Swipes (Signature Ability)**
>
> | **Charge, Melee, Strike, Weapon** |                 **Main action** |
> |-----------------------------------|--------------------------------:|
> | **📏 Melee 1**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; the griffon can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
> - **12-16:** 10 damage; the griffon [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
> - **17+:** 13 damage; the griffon [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
>
> **Effect:** If this ability is used as part of the Charge main action, the griffon can [grab](scc.v1:mcdm.heroes.v1/condition/grabbed) one of the targets.

> 🔳 **Crack the Earth**
>
> | **Area, Ranged**       |                  **Maneuver** |
> |------------------------|------------------------------:|
> | **📏 3 cube within 8** | **🎯 Each enemy in the area** |
>
> **Special:** The griffon must be flying and must have a creature or object [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
>
> **Effect:** The griffon flies up to half their speed toward the ground, then sends the creature or object they've [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) hurtling down. The creature or object hits the ground to turn the area into an impact crater, and takes falling damage that can't be reduced in any way.
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage; A < 1 [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 9 damage; A < 2 [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> 🔳 **Wing Buffet (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**                   |                               **Maneuver** |
> |----------------------------|-------------------------------------------:|
> | **📏 4 x 2 line within 1** | **🎯 Each creature or object in the area** |
>
> **Special:** A target object must be size 2 or smaller.
>
> **Power Roll + 2:**
>
> - **≤11:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; A < 0 the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is vertical
> - **12-16:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; A < 1 the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is vertical
> - **17+:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; A < 2 the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is vertical

> ❗️ **Zephyr Feint (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The griffon takes damage.
>
> **Effect:** The griffon halves the damage, ignores any nondamaging effects associated with it, and [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.

> ⭐️ **Beast of Prey**
>
> While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the griffon, a creature has a double bane on the Escape Grab maneuver.

> ⭐️ **Steady**
>
> Any power roll that could knock the griffon or their rider [prone](scc.v1:mcdm.heroes.v1/condition/prone) takes a bane.
