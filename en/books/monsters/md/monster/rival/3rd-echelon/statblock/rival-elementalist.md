---
agility: 2
ev: "40"
free_strike: 8
intuition: 3
keywords:
    - Humanoid
    - Rival
level: 8
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 4
role: Controller
scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-elementalist
size: 1M
speed: 5
stability: 1
stamina: "180"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 8       |   Elite Controller    |        EV 40         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **180**<br>Stamina |  **1**<br>Stability   | **8**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **0**<br>Might   | **+2**<br>Agility |  **+4**<br>Reason  |  **+3**<br>Intuition  |  **0**<br>Presence   |

> 🏹 **Verdant Rains ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Green, Magic, Ranged, Strike** |                 **Main action** |
> |----------------------------------|--------------------------------:|
> | **📏 Ranged 10**                 | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 12 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 2 4 acid damage
> - **12-16:** 17 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 3 6 acid damage
> - **17+:** 21 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 4 8 acid damage
>
> **Effect:** One ally within distance ends one [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) on themself.

> 🔳 **The Chasm Engulfs (4 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Green, Magic, Ranged** |               **Main action** |
> |--------------------------------|------------------------------:|
> | **📏 5 cube within 10**        | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 damage
> - **12-16:** 10 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
> - **17+:** 14 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies until the end of the encounter. Any enemy in the area has acid [weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5.

> ❗️ **Maw of the Abyss**
>
> | **Magic, Void** | **Triggered action** |
> |-----------------|---------------------:|
> | **📏 Self**     |          **🎯 Self** |
>
> **Trigger:** The elementalist takes damage.
>
> **Effect:** The elementalist can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 4 squares. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the space they leave or appear in takes 4 corruption damage.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the elementalist chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the elementalist and the creature can add a d3 roll to power rolls they make against each other.
