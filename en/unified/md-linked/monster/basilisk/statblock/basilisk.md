---
agility: 0
ev: "12"
free_strike: 5
immunities:
    - Poison 4
intuition: -1
keywords:
    - Basilisk
    - Beast
level: 1
might: 2
name: Basilisk
organization: Elite
presence: -1
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.basilisk.statblock/basilisk
size: "2"
speed: 8
stability: 2
stamina: "80"
type: statblock
---

|     Basilisk, Beast      |         -         |      Level 1      |      Elite Brute      |        EV 12         |
|:------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|      **2**<br>Size       |  **8**<br>Speed   | **80**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **Poison 4**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|     **+2**<br>Might      | **+0**<br>Agility | **-3**<br>Reason  |  **-1**<br>Intuition  |  **-1**<br>Presence  |

> 🗡 **Noxious Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **[Main Action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 poison damage
> - **12-16:** 10 poison damage
> - **17+:** 13 poison damage
>
> **Effect:** This ability gains an edge against targets the basilisk has previously dealt poison damage to.

> 🔳 **Petrifying Eye Beams**
>
> | **Area, Magic**            |   **[Maneuver](../../../rule/combat/turn.md)** |
> |----------------------------|---------------:|
> | **📏 5 x 2 line within 1** | **🎯 Special** |
>
> **Special:** The area extends from both the basilisk’s eyes, and this ability targets the first creature without cover on either side of the area.
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** M < 1 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** [Slowed](../../../condition/slowed.md) (save ends); or if M < 2 [restrained](../../../condition/restrained.md) (save ends)
>
> **Effect:** If a target is already [slowed](../../../condition/slowed.md), the potency increases by 1 for that target. A target [restrained](../../../condition/restrained.md) this way magically begins to turn to stone, and a target who ends two consecutive turns [restrained](../../../condition/restrained.md) this way is petrified. A target [restrained](../../../condition/restrained.md) this way or a creature adjacent to them can use a main action to cut encroaching stone from the target’s body, dealing 8 damage to the target that can’t be reduced in any way and ending this effect.

> 🔳 **Poison Fumes (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Magic**        |               **[Main action](../../../rule/combat/turn.md)** |
> |------------------------|------------------------------:|
> | **📏 3 cube within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 poison damage; M < 0 [weakened](../../../condition/weakened.md) (save ends)
> - **12-16:** 6 poison damage; M < 1 [weakened](../../../condition/weakened.md) and [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 9 poison damage; M < 2 [weakened](../../../condition/weakened.md) and [slowed](../../../condition/slowed.md) (save ends)

> ❗️ **Lash Out**
>
> | **Area** | **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |-----------------------------|------------------------------:|
> | **📏 1 burst**     | **🎯 Each enemy in the area** |
>
> **Trigger:** The basilisk takes damage from a melee ability.
>
> **Effect:** Each target takes 5 damage. Any target who has A < 2 is also [bleeding](../../../condition/bleeding.md) (save ends).

> ⭐️ **Calcifying Presence**
>
> The area within 3 squares of the basilisk is difficult terrain for enemies.
