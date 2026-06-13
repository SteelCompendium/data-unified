---
agility: 4
ev: "48"
free_strike: 10
intuition: 2
keywords:
    - Humanoid
    - Rival
level: 10
might: 5
name: Rival Fury
organization: Elite
presence: 3
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.rivals.4th-echelon.statblock/rival-fury
size: 1M
speed: 5
stability: 3
stamina: "260"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 10      |      Elite Brute      |         EV 48         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:---------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **260**<br>Stamina |  **3**<br>Stability   | **10**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |   **-**<br>Weakness   |
|  **+5**<br>Might  | **+4**<br>Agility |  **0**<br>Reason   |  **+2**<br>Intuition  |  **+3**<br>Presence   |

> 🗡 **Seismic Crush ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 4
> - **12-16:** 21 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 5
> - **17+:** 25 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 6
>
> **2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** Each target who has M < 4 is [bleeding](scc:mcdm.heroes.v1/condition/bleeding) and [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends).

> 🗡 **Death Grip (4 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 damage; M < 3 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 21 damage; M < 4 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 25 damage; M < 5 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** The target must be the fury's size or smaller. While the target is [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the fury and their allies have a double edge on [strikes](scc:mcdm.heroes.v1/rule.combat/strike) against them.

> ⭐️ **Devastate**
>
> Once per turn, when the fury [force moves](scc:mcdm.heroes.v1/movement/forced-movement) a creature or object, or [shifts](scc:mcdm.heroes.v1/movement/shifting) [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to a creature or object, they can use a [signature ability](scc:mcdm.heroes.v1/rule.combat/signature-ability) against that creature or object that has a double edge.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the fury chooses one creature within their [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect). Both the fury and the creature can add a d3 roll to power rolls they make against each other.
