---
agility: 1
ev: "48"
file_basename: logostician-vesper
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 10
intuition: 4
item_id: logostician-vesper
item_name: Logostician Vesper
keywords:
    - Soulless
    - War Dog
level: 10
might: 2
name: Logostician Vesper
organization: Elite
presence: 1
reason: 5
role: Controller
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/logostician-vesper
size: "2"
source: mcdm.monsters.v1
speed: 10
stability: 3
stamina: "253"
type: statblock
---

| Soulless, War Dog |         -         |      Level 10       |         Elite Controller          |        EV 48         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |  **10**<br>Speed  | **253**<br>Stamina |  **3**<br>Stability   | **10**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+1**<br>Agility |  **+5**<br>Reason  |  **+4**<br>Intuition  |  **+1**<br>Presence  |

> 🔳 **Portal to the Firing Line ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Area, Ranged, Weapon**    |                             **Main action** |
> |-----------------------------|--------------------------------------------:|
> | **📏 5 x 3 line within 15** | **🎯 Each creature and object in the area** |
>
> **Special:** This ability targets only non-[prone](../../../../condition/prone.md) creatures.
>
> **Power Roll + 5:**
>
> - **≤11:** 8 damage
> - **12-16:** 12 damage; I < 4 [slowed](../../../../condition/slowed.md) (save ends)
> - **17+:** 15 damage; I < 5 [slowed](../../../../condition/slowed.md) (save ends)
>
> **Effect:** A target creature can choose to drop [prone](../../../../condition/prone.md), in which case the ability takes a bane against them.
>
> **2 [Malice](../../../../rule/monster/malice.md):** The area remains active until Vesper is reduced to 0 [Stamina](../../../../rule/health/stamina.md) or until the end of the encounter. Any non-[prone](../../../../condition/prone.md) enemy who enters the area for the first time in a round or starts their turn there takes 15 damage, or 7 damage if they choose to fall [prone](../../../../condition/prone.md).

> 🔳 **Portal to the Mantle (3 [Malice](../../../../rule/monster/malice.md))**
>
> | **Area, Magic, Ranged** |                             **Main action** |
> |-------------------------|--------------------------------------------:|
> | **📏 3 cube within 15** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 fire damage
> - **12-16:** 12 fire damage
> - **17+:** 15 fire damage
>
> **Effect:** The area is [difficult terrain](../../../../movement/difficult-terrain.md). Any creature who enters the area for the first time in a round or starts their turn there takes 10 fir damage. Until the end of the encounter, the size of the area increases by 1 at the start of each round.

> 🔳 **Portal to the Void**
>
> | **Area, Magic, Ranged** |                                **Maneuver** |
> |-------------------------|--------------------------------------------:|
> | **📏 5 cube within 15** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** A < 4 [pull](../../../../movement/forced-movement.md) 3 toward the center of the area
> - **12-16:** A < 5 [pull](../../../../movement/forced-movement.md) 3 toward the center of the area
> - **17+:** [Pull](../../../../movement/forced-movement.md) 3 toward the center of the area
>
> **Effect:** A portal appears at the center of the area. Any creature at the center of the area when this ability is used or who is pulled into the center for the first time in a round takes 10 sonic damage.
>
> **2 [Malice](../../../../rule/monster/malice.md):** The area remains active and deals its damage until Vesper is reduced to 0 [Stamina](../../../../rule/health/stamina.md) or until the end of the encounter. Any creature who enters the area and has A < 4 is [pulled](../../../../movement/forced-movement.md) 3 squares toward the center of the area. Any creature who starts their turn in the area and has M < 4 is [slowed](../../../../condition/slowed.md) until the end of their turn.

> ❗️ **Portal to the Sky**
>
> | **Ranged**      | **Triggered action** |
> |-----------------|---------------------:|
> | **📏 Ranged 3** |     **🎯 One enemy** |
>
> **Trigger:** The target moves within distance of Vesper.
>
> **Effect:** The target is dropped through a portal, which [teleports](../../../../movement/teleport.md) them up to 7 squares above a space within 15 squares.

> ⭐️ **Living Logistics Network**
>
> Each ally who starts their turn within 10 squares of Vesper can [teleport](../../../../movement/teleport.md) whenever they willingly move until the end of their turn. Whenever an affected ally [teleports](../../../../movement/teleport.md), they deal an extra 5 damage on their next strike.

> ⭐️ **Crash and Burn**
>
> When Vesper is reduced to 0 [Stamina](../../../../rule/health/stamina.md), they move up to their speed and then explode, dealing 4d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object. Any enemy who takes more than 14 damage this way vertically [slides](../../../../movement/forced-movement.md) 5 squares.
