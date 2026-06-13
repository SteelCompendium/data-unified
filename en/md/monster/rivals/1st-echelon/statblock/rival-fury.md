---
agility: 1
ev: "16"
free_strike: 5
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 2
might: 2
name: Rival Fury
organization: Elite
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.rivals.1st-echelon.statblock/rival-fury
size: 1M
speed: 5
stability: 3
stamina: "100"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 2       |      Elite Brute      |        EV 16         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **100**<br>Stamina |  **3**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+1**<br>Agility |  **0**<br>Reason   |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Brutal Impact ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 11 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 14 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
>
> **2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** Each target who has M < 1 is [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends).

> 🗡 **Let's Tussle (2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage; M < 0 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 13 damage; M < 1 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 16 damage; M < 2 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** The target must be the fury's size or smaller. While the target is [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the fury gains an edge on [strikes](scc:mcdm.heroes.v1/rule.combat/strike) against them.

> ⭐️ **Overwhelm**
>
> Once per turn, when the fury [force moves](scc:mcdm.heroes.v1/movement/forced-movement) a creature or object, or [shifts](scc:mcdm.heroes.v1/movement/shifting) [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to a creature or object, they can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that creature or object.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the fury chooses one creature within their [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect). Both the fury and the creature can add a d3 roll to power rolls they make against each other.
