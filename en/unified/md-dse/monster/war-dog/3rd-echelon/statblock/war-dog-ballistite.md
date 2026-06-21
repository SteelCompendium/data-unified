---
agility: -2
ev: "10"
file_basename: war-dog-ballistite
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 4
intuition: 3
item_id: war-dog-ballistite
item_name: War Dog Ballistite
keywords:
    - Soulless
    - War Dog
level: 8
might: 4
name: War Dog Ballistite
organization: Horde
presence: 2
reason: 2
role: Artillery
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-ballistite
size: 1L
source: mcdm.monsters.v1
speed: 0
stability: 5
stamina: "72"
type: statblock
---

| Soulless, War Dog |         -         |      Level 8      |    Horde Artillery    |        EV 10         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1L**<br>Size   |  **0**<br>Speed   | **72**<br>Stamina |  **5**<br>Stability   | **4**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+4**<br>Might  | **-2**<br>Agility | **+2**<br>Reason  |  **+3**<br>Intuition  |  **+2**<br>Presence  |

> 🏹 **Biokinetic Ballista ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Ranged, Strike, Weapon** |                 **Main action** |
> |----------------------------|--------------------------------:|
> | **📏 Ranged 15**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
>
> **Effect:** Any target [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) into an obstacle is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone), and if they have M < 3 they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).

> 🔳 **Kill Zone (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic, Ranged** |   **Maneuver** |
> |-------------------------|---------------:|
> | **📏 3 cube within 12** | **🎯 Special** |
>
> **Effect:** Until the start of the ballistite's next turn, the area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain), and any ranged ability targeting an enemy in the area deals an extra 8 damage.

> ⭐️ **Set Up and Tear Down**
>
> At the start of each of the ballistite's turns, they can gain a +4 bonus to speed until the end of their turn. While their speed is greater than 0 by any means, they can't use main actions or maneuvers.

> ⭐️ **Loyalty Collar**
>
> When the ballistite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
