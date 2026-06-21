---
agility: 0
ev: "28"
file_basename: rival-tactician
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 7
intuition: 0
item_id: rival-tactician
item_name: Rival Tactician
keywords:
    - Humanoid
    - Rival
level: 5
might: 3
name: Rival Tactician
organization: Elite
presence: 1
reason: 2
role: Artillery
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-tactician
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "120"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 5       |    Elite Artillery    |        EV 28         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **7**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+3**<br>Might  | **0**<br>Agility  |  **+2**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence  |

> 🏹 **Mark Targets ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Ranged, Strike, Weapon** |                 **Main action** |
> |----------------------------|--------------------------------:|
> | **📏 Ranged 10**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage
> - **12-16:** 15 damage
> - **17+:** 18 damage
>
> **3 [Malice](../../../../rule/monster/malice.md):** Two allies within distance can use a [signature ability](../../../../rule/combat/signature-ability.md) against the same target.

> 🏹 **Preserve and Protect (3 [Malice](../../../../rule/monster/malice.md))**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 5**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 11 damage; M < 1 [weakened](../../../../condition/weakened.md) (save ends)
> - **12-16:** 16 damage; M < 2 [weakened](../../../../condition/weakened.md) (save ends)
> - **17+:** 21 damage; M < 3 [weakened](../../../../condition/weakened.md) (save ends)
>
> **Effect:** One ally [adjacent](../../../../rule/combat/adjacent.md) to the target regains 7 [Stamina](../../../../rule/health/stamina.md).

> ❗️ **Take the Opening**
>
> | **Ranged**       |        **Triggered action** |
> |------------------|----------------------------:|
> | **📏 Ranged 10** | **🎯 The triggering enemy** |
>
> **Trigger:** An enemy within distance willingly moves.
>
> **Effect:** At any point during the movement, the tactician and one ally within distance can each make a [free strike](../../../../feature/common/main-actions/free-strike.md) against the target.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the tactician chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the tactician and the creature can add a d3 roll to power rolls they make against each other.
