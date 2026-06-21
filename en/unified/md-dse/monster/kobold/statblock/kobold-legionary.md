---
agility: 1
ev: "3"
file_basename: kobold-legionary
file_dpath: monster/kobold/statblock
free_strike: 1
intuition: 0
item_id: kobold-legionary
item_name: Kobold Legionary
keywords:
    - Humanoid
    - Kobold
level: 1
might: 2
name: Kobold Legionary
organization: Horde
presence: 0
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-legionary
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "20"
type: statblock
---

| Humanoid, Kobold  |         -         |      Level 1      |    Horde Defender     |         EV 3         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1S**<br>Size   |  **5**<br>Speed   | **20**<br>Stamina |  **0**<br>Stability   | **1**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+1**<br>Agility |  **0**<br>Reason  |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Gladius (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (EoT)
> - **12-16:** 4 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (EoT)
> - **17+:** 5 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (EoT)
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** If the legionary is acting as a [captain](scc.v1:mcdm.monsters.v1/rule.monster/captain), they and each member of their [squad](scc.v1:mcdm.monsters.v1/rule.monster/squad) [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares before this ability is used.

> 🗡 **Shield Bash**
>
> | **Melee, Strike, Weapon** |                  **Maneuver** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < 0 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 3 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> ⭐️ **Shield? Shield!**
>
> While [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an ally who also has this trait, the legionary has stability 1, has cover, and grants cover to allies.
