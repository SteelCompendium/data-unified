---
agility: 3
ev: "32"
file_basename: devil-high-judge
file_dpath: monster/devil/statblock
free_strike: 6
immunities:
    - Fire 5
intuition: 1
item_id: devil-high-judge
item_name: Devil High Judge
keywords:
    - Devil
    - Infernal
level: 6
might: 1
movement: Fly
name: Devil High Judge
organization: Leader
presence: 2
reason: 0
scc: mcdm.monsters.v1/monster.devil.statblock/devil-high-judge
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 2
stamina: "181"
type: statblock
---

|    Devil, Infernal     |          -          |      Level 6       |        Leader         |        EV 32         |
|:----------------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size     |   **7**<br>Speed    | **181**<br>Stamina |  **2**<br>Stability   | **6**<br>Free Strike |
| **Fire 5**<br>Immunity | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+1**<br>Might     |  **+3**<br>Agility  |  **+0**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🏹 **Infernal Decree (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                   **Main action** |
> |---------------------------|----------------------------------:|
> | **📏 Ranged 12**          | **🎯 Three creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 10 damage; P < 2 the target can't hide (save ends)
> - **12-16:** 15 damage; P < 3 the target can't hide (save ends)
> - **17+:** 19 damage; P < 4 the target can't hide (save ends)
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** While a target is unable to hide this way, any strike against them made by a devil gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).

> 🏹 **Compel the Jury**
>
> | **Magic, Ranged, Strike** |         **Maneuver** |
> |---------------------------|---------------------:|
> | **📏 Ranged 12**          | **🎯 Two creatures** |
>
> **Power Roll + 4:**
>
> - **≤11:** I < 2 the target is charmed (save ends)
> - **12-16:** I < 3 the target is charmed (save ends)
> - **17+:** I < 4 the target is charmed (save ends)
>
> **Effect:** While charmed this way, a creature treats the high judge as an ally, and the high judge can spend 1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) on their turn to make that creature move up to 3 squares.

> ❗️ **Devilish Suggestion (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |           **Triggered action** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature targets the high judge with a strike.
>
> **Effect:** The target makes a **Presence test**.
>
> - **≤11:** The target is charmed (save ends).
> - **12-16:** The high judge chooses a new target for the strike.
> - **17+:** The target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the strike.
>
> While charmed this way, a creature treats the high judge as an ally, and the high judge can spend 1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) on their turn to make that creature move up to 3 squares.

> ⭐️ **End Effect**
>
> At the end of each of their turns, the high judge can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

> ⭐️ **True Name**
>
> If a creature within 10 squares speaks the high judge's true name, the high judge loses their damage immunities, any nondamaging effects of their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability), and their Devilish Suggestion [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) until the end of the encounter.

> ☠️ **All Rise ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Effect:** The target makes a **Presence test**.
>
> - **≤11:** 15 psychic damage; the target is charmed (save ends)
> - **12-16:** 12 psychic damage; the target is charmed (save ends)
> - **17+:** 7 psychic damage
>
> While charmed this way, a creature treats the high judge as an ally, and the high judge can spend 1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) on their turn to make that creature move up to 3 squares.

> ☠️ **Heed My Decree ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Area**       |                                 **-** |
> |----------------|--------------------------------------:|
> | **📏 5 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed. The high judge can make each creature charmed by All Rise, Compel the Jury, or Devilish Suggestion move up to half that creature's speed.

> ☠️ **Deceptive Stratagem ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Magic, Ranged** |               **-** |
> |-------------------|--------------------:|
> | **📏 Ranged 12**  | **🎯 One creature** |
>
> **Effect:** If the target is an ally or a creature charmed by All Rise, Compel the Jury, or Devilish Suggestion, the high judge and the target [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to swap places. Each ally within 12 squares of the high judge can then make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a target of the high judge's choice. Each creature charmed by All Rise, Compel the Jury, or Devilish Suggestion makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a target of the high judge's choice.
