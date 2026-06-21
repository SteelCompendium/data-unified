---
agility: 2
ev: "12"
file_basename: radenwight-maestro
file_dpath: monster/radenwight/statblock
free_strike: 4
intuition: 0
item_id: radenwight-maestro
item_name: Radenwight Maestro
keywords:
    - Humanoid
    - Radenwight
level: 1
might: -2
movement: Climb
name: Radenwight Maestro
organization: Leader
presence: 3
reason: 0
scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-maestro
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "80"
type: statblock
---

| Humanoid, Radenwight |           -           |      Level 1      |        Leader         |        EV 12         |
|:--------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|    **1S**<br>Size    |    **5**<br>Speed     | **80**<br>Stamina |  **1**<br>Stability   | **4**<br>Free Strike |
|  **-**<br>Immunity   | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|   **-2**<br>Might    |   **+2**<br>Agility   |  **0**<br>Reason  |  **0**<br>Intuition   |  **+3**<br>Presence  |

> ❇️ **Cacophony ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 3 sonic damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1, the maestro can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
> - **12-16:** 6 sonic damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3, the maestro [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
> - **17+:** 8 sonic damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5, the maestro [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 5 squares
>
> **Effect:** Each ally within distance can use Ready Rodent as a free triggered action once before the end of the round.

> 🏹 **Tempo Changer**
>
> | **Magic, Ranged, Strike** |       **Maneuver** |
> |---------------------------|-------------------:|
> | **📏 Ranged 10**          | **🎯 Two enemies** |
>
> **Power Roll + 3:**
>
> - **≤11:** P < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** P < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** P < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Each ally within 3 squares of any target has a +2 bonus to speed until the end of their next turn.

> ❗️ **Ever-Ready Rodent (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |      **Free triggered action** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to an ally or takes damage from an ally.
>
> **Effect:** The maestro makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.

> ⭐️ **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect)**
>
> At the end of each of their turns, the maestro can take 5 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.

> ☠️ **Overture ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area**        |                        **-** |
> |-----------------|-----------------------------:|
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed or take the Defend action.

> ☠️ **Solo Act ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Ranged**       |               **-** |
> |------------------|--------------------:|
> | **📏 Ranged 15** | **🎯 One creature** |
>
> **Effect:** Until the end of their next turn, the target halves any damage they take, gains a +4 damage bonus to [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike), and has their speed doubled.

> ☠️ **Rondo of Rat ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area**        |                             **-** |
> |-----------------|----------------------------------:|
> | **📏 10 burst** | **🎯 Each dead ally in the area** |
>
> **Effect:** Each target stands, makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike), then falls dead again. Any ally of the targets can use Ready Rodent as a free triggered action once in conjunction with these free strikes.
