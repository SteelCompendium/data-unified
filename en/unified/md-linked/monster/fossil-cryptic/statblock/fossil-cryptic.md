---
agility: 2
ev: "48"
free_strike: 5
intuition: 1
keywords:
    - Elemental
level: 2
might: 3
movement: Burrow
name: Fossil Cryptic
organization: Solo
presence: 0
reason: 1
scc: mcdm.monsters.v1/monster.fossil-cryptic.statblock/fossil-cryptic
size: 1L
speed: 8
stability: 3
stamina: "250"
type: statblock
---

|     Elemental     |           -            |      Level 2       |         Solo          |        EV 48         |
|:-----------------:|:----------------------:|:------------------:|:---------------------:|:--------------------:|
|  **1L**<br>Size   |     **8**<br>Speed     | **250**<br>Stamina |  **3**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **Burrow**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+3**<br>Might  |   **+2**<br>Agility    |  **+1**<br>Reason  |  **+1**<br>Intuition  |  **0**<br>Presence   |

> ☠️ **Solo Monster**
>
> **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the cryptic can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The cryptic can take two turns each round. They can't take turns consecutively.

> ⭐️ **Churning Trunk**
>
> The cryptic is constantly surrounded by a 1 aura of swirling debris that obscures their form. Ranged abilities that target the cryptic take a bane. Additionally, any enemy who enters the aura for the first time in a round or starts their turn there takes 5 damage.

> ⭐️ **Seismic Step**
>
> The cryptic ignores [difficult terrain](../../../movement/difficult-terrain.md). Additionally, they have line of effect to any creature with concealment if that creature is touching the ground.

> 🗡 **Sand Slam (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; A < 1 [slide](../../../movement/forced-movement.md) 2
> - **12-16:** 12 damage; A < 2 [slide](../../../movement/forced-movement.md) 2, [prone](../../../condition/prone.md)
> - **17+:** 15 damage; A < 3 [slide](../../../movement/forced-movement.md) 3, [prone](../../../condition/prone.md) and can't stand (EoT)
>
> **Effect:** If a target made [prone](../../../condition/prone.md) this way is already [prone](../../../condition/prone.md), they are instead [restrained](../../../condition/restrained.md) (EoT).

> 🔳 **Stone Bone Storm**
>
> | **Area**                   |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 6 x 1 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 4 damage; M < 1 [push](../../../movement/forced-movement.md) 2
> - **12-16:** 7 damage; M < 2 [prone](../../../condition/prone.md)
> - **17+:** 10 damage; M < 3 [prone](../../../condition/prone.md)
>
> **Effect:** The cryptic reforms their body and appears in an unoccupied space in the area.

> 🏹 **Stoneshift**
>
> | **Ranged**      |                                **Maneuver** |
> |-----------------|--------------------------------------------:|
> | **📏 Ranged 5** | **🎯 One creature or object on the ground** |
>
> **Effect:** The cryptic [slides](../../../movement/forced-movement.md) the target up to 3 squares.
>
> **2 [Malice](../../../rule/monster/malice.md):** The ability targets one additional target.

> ❗️ **Dissipate (1 [Malice](../../../rule/monster/malice.md))**
>
> | **-**       | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The cryptic takes damage.
>
> **Effect:** The cryptic halves the damage, ignores any nondamaging effects associated with it, and [shifts](../../../movement/shifting.md) up to 3 squares.

> ❗️ **Shatterstone (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area**       |          **Triggered action** |
> |----------------|------------------------------:|
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Trigger:** The cryptic uses the Dig maneuver to resurface.
>
> **Effect:** Before using the Dig maneuver, the cryptic moves up to their speed. They then create the burst when they breach the surface.
>
> **Power Roll + 3:**
>
> - **≤11:** 4 damage; [push](../../../movement/forced-movement.md) 2
> - **12-16:** 7 damage; [push](../../../movement/forced-movement.md) 3, [prone](../../../condition/prone.md)
> - **17+:** 10 damage; [push](../../../movement/forced-movement.md) 4, [prone](../../../condition/prone.md)

> ☠️ **First Warning Quake ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area**        |                         **-** |
> |-----------------|------------------------------:|        
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Special:** A target must be on the ground.
>
> **Effect:** Each target makes a **Might test**.
>
> - **≤11:** [Prone](../../../condition/prone.md) and can't stand (EoT)
> - **12-16:** [Prone](../../../condition/prone.md)
> - **17+:** No effect

> ☠️ **Final Warning Fissure ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **Area**       |                         **-** |
> |----------------|------------------------------:|
> | **📏 5 burst** | **🎯 Each enemy in the area** |
>
> **Special:** A target must be on the ground.
>
> **Effect:** The area drops 2 squares and is [difficult terrain](../../../movement/difficult-terrain.md). Each target enemy falls, while each target ally drops safely. Additionally, each target enemy makes an **Agility test**.
>
> - **≤11:** 9 damage; [prone](../../../condition/prone.md)
> - **12-16:** 5 damage
> - **17+:** The target moves to the nearest unoccupied space outside the area.

> ☠️ **No Escape ([Villain Action](../../../rule/monster/villain-action.md) 3)**
> 
> | **Ranged**       |                           **-** |
> |------------------|--------------------------------:|
> | **📏 Ranged 10** | **🎯 Two creatures or objects** |
> 
> **Effect:** The cryptic makes an initial power roll that calls down stone pillars from the ceiling.
> 
> **Power Roll + 3:**
> 
> - **≤11:** 5 damage; [prone](../../../condition/prone.md); M < 1 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** 9 damage; [prone](../../../condition/prone.md); M < 2 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** 12 damage; [prone](../../../condition/prone.md); M < 3 [restrained](../../../condition/restrained.md) (save ends)
> 
> The cryptic then makes a second power roll that raises stone pillars from the floor (**📏 Ranged 10** | **🎯 Two creatures or objects on the ground**)
> 
> **Power Roll + 3:**
> 
> - **≤11:** 2 damage; vertical [slide](../../../movement/forced-movement.md) 2
> - **12-16:** 3 damage; vertical [slide](../../../movement/forced-movement.md) 4
> - **17+:** 4 damage; vertical [slide](../../../movement/forced-movement.md) 6; if this movement brings the target into contact with the ceiling, they are [restrained](../../../condition/restrained.md) (save ends).
