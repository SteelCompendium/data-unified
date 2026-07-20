---
agility: 0
ev: "10"
free_strike: 5
intuition: 0
keywords:
    - Dwarf
    - Humanoid
level: 3
might: 2
name: Dwarf Shieldwall
organization: Platoon
presence: 1
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-shieldwall
size: 1M
speed: 5
stability: 4
stamina: "72"
type: statblock
---

|  Dwarf, Humanoid  |         -         |      Level 3      |   Platoon Defender    |        EV 10         | 
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:| 
|  **1M**<br>Size   |  **5**<br>Speed   | **72**<br>Stamina |  **4**<br>Stability   | **5**<br>Free Strike | 
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   | 
|  **+2**<br>Might  | **+0**<br>Agility | **+0**<br>Reason  |  **+0**<br>Intuition  |  **+1**<br>Presence  |

> 🗡 **Wide Axe (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 10 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **17+:** 13 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
>
> **Effect:** The shieldwall can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square to remain [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target. A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** This ability targets one additional target.

> ❗️ **Intercepting Shield (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** A creature makes a strike against an ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the shieldwall.
>
> **Effect:** The shieldwall becomes the target of the triggering strike and halves the damage.

> ⭐️ **Call to the Wall**
>
> Whenever a creature deals damage to or takes damage from the shieldwall, the shieldwall can make that creature [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) until the end of the creature's next turn.
