---
agility: 0
ev: "16"
free_strike: 5
intuition: 0
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

> 🗡 **Club Swing ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 11 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 4
> - **17+:** 14 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 6, [prone](scc:mcdm.heroes.v1/condition/prone)
>
> **Effect:** Any target who takes damage from this [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) takes an extra 4 damage.

> 🗡 **Grabby Hand (1 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |                  **Maneuver** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage; [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 14 damage; [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** A target [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way takes a bane on the Escape Grab maneuver.

> 🔳 **People Bowling (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Weapon**           |                                **Maneuver** |
> |----------------------------|--------------------------------------------:|
> | **📏 6 x 1 line within 1** | **🎯 Each creature and object in the area** |
>
> **Effect:** The goon must have a size 1 creature or object [grabbed](scc:mcdm.heroes.v1/condition/grabbed), which they hurl across the area, ending the grab. The hurled creature or object is targeted by the ability, and lands in the last square of the line or the nearest unoccupied square of the goon's choice.
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage; [prone](scc:mcdm.heroes.v1/condition/prone)

> ❗️ **Swat the Fly**
>
> | **Melee**      |                     **Triggered action** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance moves or [shifts](scc:mcdm.heroes.v1/movement/shifting) away from the goon.
>
> **Effect:** The goon [slides](scc:mcdm.heroes.v1/movement/forced-movement) the target up to 5 squares.

> ⭐️ **Defiant Anger**
>
> While [winded](scc:mcdm.heroes.v1/rule.health/winded), the goon has damage immunity 2.
