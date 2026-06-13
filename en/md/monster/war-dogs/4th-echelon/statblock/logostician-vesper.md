---
agility: 1
ev: "48"
free_strike: 10
intuition: 4
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
scc: mcdm.monsters.v1/monster.war-dogs.4th-echelon.statblock/logostician-vesper
size: "2"
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

> 🔳 **Portal to the Firing Line ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Area, Ranged, Weapon**    |                             **Main action** |
> |-----------------------------|--------------------------------------------:|
> | **📏 5 x 3 line within 15** | **🎯 Each creature and object in the area** |
>
> **Special:** This ability targets only non-[prone](scc:mcdm.heroes.v1/condition/prone) creatures.
>
> **Power Roll + 5:**
>
> - **≤11:** 8 damage
> - **12-16:** 12 damage; I < 4 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 15 damage; I < 5 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** A target creature can choose to drop [prone](scc:mcdm.heroes.v1/condition/prone), in which case the ability takes a bane against them.
>
> **2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** The area remains active until Vesper is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) or until the end of the encounter. Any non-[prone](scc:mcdm.heroes.v1/condition/prone) enemy who enters the area for the first time in a round or starts their turn there takes 15 damage, or 7 damage if they choose to fall [prone](scc:mcdm.heroes.v1/condition/prone).

> 🔳 **Portal to the Mantle (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
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
> **Effect:** The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain). Any creature who enters the area for the first time in a round or starts their turn there takes 10 fir damage. Until the end of the encounter, the size of the area increases by 1 at the start of each round.

> 🔳 **Portal to the Void**
>
> | **Area, Magic, Ranged** |                                **Maneuver** |
> |-------------------------|--------------------------------------------:|
> | **📏 5 cube within 15** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** A < 4 [pull](scc:mcdm.heroes.v1/movement/forced-movement) 3 toward the center of the area
> - **12-16:** A < 5 [pull](scc:mcdm.heroes.v1/movement/forced-movement) 3 toward the center of the area
> - **17+:** [Pull](scc:mcdm.heroes.v1/movement/forced-movement) 3 toward the center of the area
>
> **Effect:** A portal appears at the center of the area. Any creature at the center of the area when this ability is used or who is pulled into the center for the first time in a round takes 10 sonic damage.
>
> **2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** The area remains active and deals its damage until Vesper is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) or until the end of the encounter. Any creature who enters the area and has A < 4 is [pulled](scc:mcdm.heroes.v1/movement/forced-movement) 3 squares toward the center of the area. Any creature who starts their turn in the area and has M < 4 is [slowed](scc:mcdm.heroes.v1/condition/slowed) until the end of their turn.

> ❗️ **Portal to the Sky**
>
> | **Ranged**      | **Triggered action** |
> |-----------------|---------------------:|
> | **📏 Ranged 3** |     **🎯 One enemy** |
>
> **Trigger:** The target moves within distance of Vesper.
>
> **Effect:** The target is dropped through a portal, which [teleports](scc:mcdm.heroes.v1/movement/teleport) them up to 7 squares above a space within 15 squares.

> ⭐️ **Living Logistics Network**
>
> Each ally who starts their turn within 10 squares of Vesper can [teleport](scc:mcdm.heroes.v1/movement/teleport) whenever they willingly move until the end of their turn. Whenever an affected ally [teleports](scc:mcdm.heroes.v1/movement/teleport), they deal an extra 5 damage on their next strike.

> ⭐️ **Crash and Burn**
>
> When Vesper is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), they move up to their speed and then explode, dealing 4d6 damage to each [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) enemy and object. Any enemy who takes more than 14 damage this way vertically [slides](scc:mcdm.heroes.v1/movement/forced-movement) 5 squares.
