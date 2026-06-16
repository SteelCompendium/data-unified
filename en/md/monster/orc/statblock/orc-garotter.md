---
agility: 2
ev: "6"
free_strike: 4
intuition: 1
keywords:
    - Humanoid
    - Orc
level: 1
might: 1
name: Orc Garotter
organization: Platoon
presence: -1
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.orc.statblock/orc-garotter
size: 1L
speed: 5
stability: 0
stamina: "30"
type: statblock
---

|   Humanoid, Orc   |         -         |      Level 1      |   Platoon Ambusher    |         EV 6         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1L**<br>Size   |  **5**<br>Speed   | **30**<br>Stamina |  **0**<br>Stability   | **4**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+1**<br>Might  | **+2**<br>Agility | **+0**<br>Reason  |  **+1**<br>Intuition  |  **-1**<br>Presence  |

> 🗡 **Dagger Feint ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage; the garroter can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square
> - **12-16:** 9 damage; the garroter [shifts](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares
> - **17+:** 12 damage; the garroter [shifts](scc:mcdm.heroes.v1/movement/shifting) up to 3 squares
>
> **Effect:** If this ability gains an edge or has a double edge, it deals an extra 4 damage.

> 🗡 **Strangle**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage; I < 1 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 12 damage; [grabbed](scc:mcdm.heroes.v1/condition/grabbed); I < 2 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
>
> **Effect:** While [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, a target can't communicate or use magic abilities.

> 👤 **Chroma Cloak (1 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**          |        **Maneuver** |
> |----------------|--------------------:|
> | **📏 -**       |            **🎯 -** |
>
> The garroter turns invisible until the end of their turn. This invisibility ends early if they take damage or use an ability.

> ⭐️ **Relentless**
>
> If the garroter is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), they can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) before dying. If the target of the free strike is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), the garroter is reduced to 1 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) instead.
