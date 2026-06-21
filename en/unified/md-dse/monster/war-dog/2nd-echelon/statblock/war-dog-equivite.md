---
agility: 3
ev: "6"
file_basename: war-dog-equivite
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 3
intuition: -2
item_id: war-dog-equivite
item_name: War Dog Equivite
keywords:
    - Soulless
    - War Dog
level: 4
might: 3
name: War Dog Equivite
organization: Horde
presence: 0
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-equivite
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "53"
type: statblock
---

| Soulless, War Dog |         -         |      Level 4      |      Horde Brute      |         EV 6         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |  **8**<br>Speed   | **53**<br>Stamina |  **2**<br>Stability   | **3**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+3**<br>Might  | **+3**<br>Agility | **-1**<br>Reason  |  **-2**<br>Intuition  |  **0**<br>Presence   |

> 🗡 **Fuse-Iron Lance ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Charge, Melee, Strike, Weapon** |               **Main action** |
> |-----------------------------------|------------------------------:|
> | **📏 Melee 2**                    | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage
> - **12-16:** 8 damage
> - **17+:** 10 damage; I < 3 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** This ability gains an edge while charging.
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The ability deals an extra 3 fire damage to the target and each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target.

> 🗡 **Blazing Charge**
>
> | **Melee, Weapon**         |   **Maneuver** |
> |---------------------------|---------------:|
> | **📏 Special; see below** | **🎯 Special** |
>
> **Effect:** The equivite moves up to their speed and ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). Any mundane size 1 object whose space they move through is destroyed. The equivite makes one power roll against each enemy whose space they move through for the first time.
>
> **Power Roll + 3:**
>
> - **≤11:** 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> ⭐️ **Loyalty Collar**
>
> When the equivite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
