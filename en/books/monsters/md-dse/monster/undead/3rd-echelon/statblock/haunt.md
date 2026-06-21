---
agility: 4
ev: "9"
file_basename: haunt
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 0
item_id: haunt
item_name: Haunt
keywords:
    - Undead
level: 7
might: -2
movement: Fly, hover
name: Haunt
organization: Horde
presence: 0
reason: -1
role: Controller
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/haunt
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 1
stamina: "40"
type: statblock
---

|                 Undead                 |             -              |      Level 7      |   Horde Controller    |         EV 9         |
|:--------------------------------------:|:--------------------------:|:-----------------:|:---------------------:|:--------------------:|
|             **2**<br>Size              |       **6**<br>Speed       | **40**<br>Stamina |  **1**<br>Stability   | **3**<br>Free Strike |
| **Corruption 7, poison 7**<br>Immunity | **Fly, hover**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **-2**<br>Might             |     **+4**<br>Agility      | **-1**<br>Reason  |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Lash Out ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 10 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 11 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
>
> **Effect:** If the target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature's space, that creature takes an additional 4 damage and the haunt [slides](scc.v1:mcdm.heroes.v1/movement/forced-movement) them up to 2 squares.

> ❇️ **Crushing Despair (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 3 damage; I < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 6 damage; I < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 7 damage; I < 4 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
>
> **Effect:** A target knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) this way can't use the [Stand Up](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/stand-up) maneuver on themself while any haunt is within 20 squares of them.

> ⭐️ **Invisible Horror**
>
> The haunt can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. They are invisible while moving using a move action. The haunt doesn't take damage from being [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into objects.
