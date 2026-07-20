---
agility: 2
ev: "20"
free_strike: 5
intuition: 2
keywords:
    - Humanoid
    - Orc
level: 3
might: 3
name: Orc Warleader
organization: Leader
presence: 2
reason: 1
scc: mcdm.monsters.v1/monster.orc.statblock/orc-warleader
size: 1M
speed: 6
stability: 2
stamina: "120"
type: statblock
---

|   Humanoid, Orc   |         -         |      Level 3       |        Leader         |        EV 20         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **6**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+3**<br>Might  | **+2**<br>Agility |  **+1**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> 🏹 **Go. ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Ranged**       | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |------------------|----------------:|
> | **📏 Ranged 10** | **🎯 One ally** |
>
> **Effect:** The target moves up to their speed and can use a main action.
>
> **1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The warleader targets two allies.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The warleader targets one ally and a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) [squad](scc.v1:mcdm.monsters.v1/rule.monster/squad).

> 🗡 **Mace Lariat**
>
> | **Melee, Strike, Weapon** |   **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|------------------:|
> | **📏 Melee 1**            | **🎯 Each enemy** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < 1 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **12-16:** 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; M < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)

> 🏹 **Lockdown (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Ranged**                |                 **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|-----------------------------:|
> | **📏 Self and ranged 10** | **🎯 Self and three allies** |
>
> **Effect:** Each target moves up to their speed and can use the [Grab](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/grab) maneuver, which gains an edge.

> ❗️ **Courtesy Call**
>
> | **Ranged**       | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |------------------|---------------------:|
> | **📏 Ranged 10** |  **🎯 One creature** |
>
> **Trigger:** The target obtains a tier 1 outcome on one power roll.
>
> **Effect:** The target has a double edge on their next power roll before the end of the encounter.

> ☠️ **Close In ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area**       |                        **-** |
> |-----------------|-----------------------------:|
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target moves up to their speed. Each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a target after this move makes an Intuition test.
>
> - **≤11:** [Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the warleader (save ends)
> - **12-16:** [Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the warleader (EoT)
> - **17+:** No effect

> ☠️ **Familial Reinforcements ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Ranged**       |       **-** |
> |------------------|------------:|
> | **📏 Ranged 10** | **🎯 Self** |
>
> **Effect:** The warleader [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, and four orc blitzers appear in unoccupied spaces within distance.

> ☠️ **I'll Do This Myself ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** Three times in succession, the warleader [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and can use Mace Lariat.

> ⭐️ **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect)**
>
> At the end of each of their turns, the warleader can take 5 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.

> ⭐️ **Relentless**
>
> If the warleader is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) before dying. If the target of the free strike is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), the warleader is reduced to 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) instead.
