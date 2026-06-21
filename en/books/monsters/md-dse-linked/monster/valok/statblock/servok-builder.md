---
agility: -2
ev: "44"
file_basename: servok-builder
file_dpath: monster/valok/statblock
free_strike: 10
intuition: -1
item_id: servok-builder
item_name: Servok Builder
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 9
might: 4
name: Servok Builder
organization: Elite
presence: -5
reason: -4
role: Brute
scc: mcdm.monsters.v1/monster.valok.statblock/servok-builder
size: "3"
source: mcdm.monsters.v1
speed: 5
stability: 8
stamina: "240"
type: statblock
---

| Construct, Servok, Soulless, Valok |         -         |       Level 9       |      Elite Brute      |        EV 44          |
|:----------------------------------:|:-----------------:|:-------------------:|:---------------------:|:---------------------:|
|           **3**<br>Size            |  **5**<br>Speed   | **240**<br>Stamina  |  **8**<br>Stability   | **10**<br>Free Strike |
|         **-**<br>Immunity          | **-**<br>Movement |          -          | **-**<br>With Captain |   **-**<br>Weakness   |
|          **+4**<br>Might           | **-2**<br>Agility |  **-4**<br>Reason   |  **-1**<br>Intuition  |   **-5**<br>Presence  |

> 🔳 **Wrecking Ball ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Area, Ranged, Weapon** |                          **Main action** |
> |--------------------------|-----------------------------------------:|
> | **📏 3 cube within 5**   | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target must make either an Agility test or an **Intuition test**.
>
> - **≤11:** 15 damage; [push](../../../movement/forced-movement.md) 5, [prone](../../../condition/prone.md)
> - **12-16:** 12 damage; [push](../../../movement/forced-movement.md) 3
> - **17+:** 8 damage

> 🗡 **Construction Arm**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 16 damage
> - **12-16:** 23 damage; [grabbed](../../../condition/grabbed.md)
> - **17+:** 28 damage; [grabbed](../../../condition/grabbed.md); M < 4 vertical [push](../../../movement/forced-movement.md) 5

> 🔳 **Lay the Foundation (3 Malice)**
>
> | **Area**                   | **Main action** |
> |----------------------------|----------------:|
> | **📏 6 x 3 line within 1** |  **🎯 Special** |
>
> **Effect:** The area is covered in wet concrete and is [difficult terrain](../../../movement/difficult-terrain.md). An enemy who starts their turn in the concrete makes a **Might test**.
>
> - **≤11:** [Restrained](../../../condition/restrained.md) (EoT)
> - **12-16:** [Slowed](../../../condition/slowed.md) (EoT)
> - **17+:** No effect

> 🔳 **Build Wall**
>
> | **Area, Ranged**       |   **Maneuver** |
> |------------------------|---------------:|
> | **📏 6 wall within 3** | **🎯 Special** |
>
> **Effect:** The builder creates a concrete wall. They can also remove any unoccupied squares of wet concrete within 3 squares of them, creating two additional squares of wall for each square of concrete removed.

> ❗️ **Sputter (1 Malice)**
>
> | **Melee**      |                **Free triggered action** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 3** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance deals damage to the builder.
>
> **Power Roll + 4:**
>
> - **≤11:** A < 2 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** A < 3 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** A < 4 [restrained](../../../condition/restrained.md) (save ends)
>
> **Effect:** While a creature is [restrained](../../../condition/restrained.md) this way, or if the target is an object, the target and their space are encased in wet concrete. A creature no longer [restrained](../../../condition/restrained.md) leaves squares of wet concrete behind.

> ⭐️ **Servok Siege Machine**
>
> The builder ignores [difficult terrain](../../../movement/difficult-terrain.md), and their abilities deal an extra 15 damage to objects.

> ⭐️ **Crafted to Perfection**
>
> The builder's shape can't be changed by any external effect.

> ⭐️ **Valiar Might**
>
> While the builder isn't [bleeding](../../../condition/bleeding.md), [weakened](../../../condition/weakened.md), or [winded](../../../rule/health/winded.md), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
