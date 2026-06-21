---
agility: 0
ev: "6"
file_basename: radenwight-piper
file_dpath: monster/radenwight/statblock
free_strike: 3
intuition: 2
item_id: radenwight-piper
item_name: Radenwight Piper
keywords:
    - Humanoid
    - Radenwight
level: 1
might: 0
movement: Climb
name: Radenwight Piper
organization: Platoon
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-piper
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

| Humanoid, Radenwight |           -           |      Level 1      |    Platoon Support    |         EV 6         |
|:--------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|    **1S**<br>Size    |    **5**<br>Speed     | **30**<br>Stamina |  **0**<br>Stability   | **3**<br>Free Strike |
|  **-**<br>Immunity   | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|    **0**<br>Might    |   **0**<br>Agility    |  **0**<br>Reason  |  **+2**<br>Intuition  |  **+1**<br>Presence  |

> ⚔️ **Piercing Trill ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Magic, Melee, Ranged, Strike** |               **Main action** |
> |----------------------------------|------------------------------:|
> | **📏 Melee 1 or ranged 10**      | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 7 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 9 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
>
> **Effect:** The piper or one ally within distance regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to the damage dealt.

> ❇️ **Vivace Vivace!**
>
> | **Area, Magic** |                 **Maneuver** |
> |-----------------|-----------------------------:|
> | **📏 3 burst**  | **🎯 Each ally in the area** |
>
> **Effect:** Each target who has used their Ready Rodent ability this round regains the use of their triggered action.
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The area increases to a 6 burst.

> ❗️ **Ready Rodent**
>
> | **Melee, Weapon** | **Triggered action** |
> |-------------------|---------------------:|
> | **📏 Melee 1**    |  **🎯 One creature** |
>
> **Trigger:** An ally deals damage to the target.
>
> **Effect:** The piper makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.

> ⭐️ **Musical Suggestion**
>
> At the end of the piper's turn, they can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) one [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature up to 2 squares, ignoring stability.
