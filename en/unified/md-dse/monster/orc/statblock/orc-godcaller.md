---
agility: 0
ev: "6"
file_basename: orc-godcaller
file_dpath: monster/orc/statblock
free_strike: 3
intuition: 1
item_id: orc-godcaller
item_name: Orc Godcaller
keywords:
    - Humanoid
    - Orc
level: 1
might: 1
name: Orc Godcaller
organization: Platoon
presence: 2
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.orc.statblock/orc-godcaller
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "30"
type: statblock
---

|   Humanoid, Orc   |         -         |      Level 1      |    Platoon Support    |         EV 6         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **6**<br>Speed   | **30**<br>Stamina |  **0**<br>Stability   | **3**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+1**<br>Might  | **+0**<br>Agility | **+0**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> ⚔️ **Power Chord ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Magic, Melee, Ranged, Strike** |               **Main action** |
> |----------------------------------|------------------------------:|
> | **📏 Melee 1 or ranged 10**      | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 sonic damage
> - **12-16:** 7 sonic damage
> - **17+:** 9 sonic damage; P < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)

> 🏹 **Cadenza**
>
> | **Magic, Ranged** | **Main action** |
> |-------------------|----------------:|
> | **📏 Ranged 10**  | **🎯 One ally** |
>
> **Effect:** The target moves up to their speed and can use a main action.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The godcaller targets a second ally.

> 🏹 **Rallying Ostinato (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |                 **Maneuver** |
> |-------------------|-----------------------------:|
> | **📏 Ranged 10**  | **🎯 Self and three allies** |
>
> **Effect:** Each target regains 15 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) until the end of the encounter.

> ⭐️ **Relentless**
>
> If the godcaller is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) before dying. If the target of the free strike is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), the godcaller is reduced to 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) instead.
