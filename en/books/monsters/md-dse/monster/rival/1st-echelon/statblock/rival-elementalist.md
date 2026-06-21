---
agility: 0
ev: "16"
file_basename: rival-elementalist
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 1
item_id: rival-elementalist
item_name: Rival Elementalist
keywords:
    - Humanoid
    - Rival
level: 2
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-elementalist
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "60"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 2      |   Elite Controller    |        EV 16         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **60**<br>Stamina |  **1**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+0**<br>Might  | **+0**<br>Agility | **+2**<br>Reason  |  **+1**<br>Intuition  |  **+0**<br>Presence  |

> 🏹 **The Writhing Green ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Green, Magic, Ranged, Strike** |                 **Main action** |
> |----------------------------------|--------------------------------:|
> | **📏 Ranged 10**                 | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 10 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 13 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3

> 🔳 **The Earth Devours (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Green, Magic, Ranged** |               **Main action** |
> |--------------------------------|------------------------------:|
> | **📏 3 cube within 10**        | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage
> - **12-16:** 5 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
> - **17+:** 8 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies until the end of the encounter. Any enemy in the area has acid [weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 2.

> ❗️ **Jaws of the Void**
>
> | **Magic, Void** | **Triggered action** |
> |-----------------|---------------------:|
> | **📏 Self**     |          **🎯 Self** |
>
> **Trigger:** The elementalist takes damage.
>
> **Effect:** The elementalist can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 2 squares. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the space they leave takes 2 corruption damage.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the elementalist chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the elementalist and the creature can add a d3 roll to power rolls they make against each other.
