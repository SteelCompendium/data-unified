---
agility: 0
ev: "16"
file_basename: ogre-goon
file_dpath: monster/ogre/statblock
free_strike: 5
intuition: 0
item_id: ogre-goon
item_name: Ogre Goon
keywords:
    - Giant
    - Ogre
level: 2
might: 2
name: Ogre Goon
organization: Elite
presence: -1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-goon
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "100"
type: statblock
---

|    Giant, Ogre    |         -         |      Level 2       |      Elite Brute      |        EV 16         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |  **5**<br>Speed   | **100**<br>Stamina |  **4**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **0**<br>Agility  |  **-1**<br>Reason  |  **0**<br>Intuition   |  **-1**<br>Presence  |

> 🗡 **Club Swing ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [push](../../../movement/forced-movement.md) 2
> - **12-16:** 11 damage; [push](../../../movement/forced-movement.md) 4
> - **17+:** 14 damage; [push](../../../movement/forced-movement.md) 6, [prone](../../../condition/prone.md)
>
> **Effect:** Any target who takes damage from this [forced movement](../../../movement/forced-movement.md) takes an extra 4 damage.

> 🗡 **Grabby Hand (1 [Malice](../../../rule/monster/malice.md))**
>
> | **Melee, Strike, Weapon** |                  **Maneuver** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage; [grabbed](../../../condition/grabbed.md)
> - **17+:** 14 damage; [grabbed](../../../condition/grabbed.md)
>
> **Effect:** A target [grabbed](../../../condition/grabbed.md) this way takes a bane on the Escape Grab maneuver.

> 🔳 **People Bowling (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Weapon**           |                                **Maneuver** |
> |----------------------------|--------------------------------------------:|
> | **📏 6 x 1 line within 1** | **🎯 Each creature and object in the area** |
>
> **Effect:** The goon must have a size 1 creature or object [grabbed](../../../condition/grabbed.md), which they hurl across the area, ending the grab. The hurled creature or object is targeted by the ability, and lands in the last square of the line or the nearest unoccupied square of the goon's choice.
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage; [prone](../../../condition/prone.md)

> ❗️ **Swat the Fly**
>
> | **Melee**      |                     **Triggered action** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance moves or [shifts](../../../movement/shifting.md) away from the goon.
>
> **Effect:** The goon [slides](../../../movement/forced-movement.md) the target up to 5 squares.

> ⭐️ **Defiant Anger**
>
> While [winded](../../../rule/health/winded.md), the goon has damage immunity 2.
