---
agility: 3
ev: "28"
file_basename: rival-null
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 6
intuition: 3
item_id: rival-null
item_name: Rival Null
keywords:
    - Humanoid
    - Rival
level: 5
might: 0
name: Rival Null
organization: Elite
presence: 0
reason: 2
role: Harrier
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-null
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "140"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 5       |     Elite Harrier     |        EV 28         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **7**<br>Speed   | **140**<br>Stamina |  **3**<br>Stability   | **6**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **0**<br>Might   | **+3**<br>Agility |  **+2**<br>Reason  |  **+3**<br>Intuition  |  **0**<br>Presence   |

> 🗡 **Agile Stride ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares; A < 1 6 damage
> - **12-16:** 14 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 4 squares; A < 2 11 damage
> - **17+:** 17 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 5 squares; A < 3 11 damage

> 🗡 **Deaden (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Psionic, Strike, Weapon** |                  **Maneuver** |
> |------------------------------------|------------------------------:|
> | **📏 Melee 1**                     | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; R < 1 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (EoT)
> - **12-16:** 14 damage; R < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 17 damage; R < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)

> ⭐️ **Inertial Shield**
>
> The first time each round that the null is targeted by a damage-dealing [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they halve the damage.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the null chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the null and the creature can add a d3 roll to power rolls they make against each other.
