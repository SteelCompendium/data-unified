---
agility: 3
ev: "48"
free_strike: 10
intuition: 4
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
might: 1
movement: Fly, hover
name: Soulbinder Psyche
organization: Elite
presence: 5
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/soulbinder-psyche
size: 1M
speed: 5
stability: 1
stamina: "220"
type: statblock
---

| Humanoid, Soulless, War Dog |             -              |      Level 10      |      Elite Hexer      |         EV 48         |
|:---------------------------:|:--------------------------:|:------------------:|:---------------------:|:---------------------:|
|       **1M**<br>Size        |       **5**<br>Speed       | **220**<br>Stamina |  **1**<br>Stability   | **10**<br>Free Strike |
|      **-**<br>Immunity      | **Fly, hover**<br>Movement |         -          | **-**<br>With Captain |   **-**<br>Weakness   |
|       **+1**<br>Might       |     **+3**<br>Agility      |  **+3**<br>Reason  |  **+4**<br>Intuition  |  **+5**<br>Presence   |

> 🏹 **Soulbind ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Magic, Ranged, Strike** |                 **[Main action](../../../../rule/combat/turn.md)** |
> |---------------------------|--------------------------------:|
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 holy damage; R < 3 the target is soulbound (save ends)
> - **12-16:** 20 holy damage; R < 4 the target is soulbound (save ends)
> - **17+:** 24 holy damage; R < 5 the target is soulbound (save ends)
>
> **Effect:** A soulbound creature can't benefit from edges or double edges, and can't gain or use [surges](../../../../rule/resource/surge.md).

> 🔳 **Soulstorm (2 [Malice](../../../../rule/monster/malice.md))**
>
> | **Area, Magic, Ranged** |               **[Main action](../../../../rule/combat/turn.md)** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 corruption damage; P < 3 [weakened](../../../../condition/weakened.md) (EoT)
> - **12-16:** 12 corruption damage; P < 4 [weakened](../../../../condition/weakened.md) (EoT)
> - **17+:** 15 corruption damage; P < 5 [weakened](../../../../condition/weakened.md) (EoT)
>
> **Effect:** The area is [difficult terrain](../../../../movement/difficult-terrain.md) until the start of Psyche's next turn At the start of each of her turns, Psyche can use a maneuver to maintain this effect, move the area up to 5 squares, and make the power roll against each creature in the area's new location.
>
> **1 [Malice](../../../../rule/monster/malice.md):** Until the start of Psyche's next turn, if this ability makes a creature [weakened](../../../../condition/weakened.md), that creature is also soulbound (save ends; see Soulbind above).

> ❇️ **Command the Awakened**
>
> | **Magic, Ranged** |                            **[Maneuver](../../../../rule/combat/turn.md)** |
> |-------------------|----------------------------------------:|
> | **📏 5 burst**    | **🎯 Each soulbound enemy in the area** |
>
> **Effect:** Each target takes 5 damage from a self-inflicted wound, and if they have M < 4 Psyche [slides](../../../../movement/forced-movement.md) them up to 5 squares.

> ❗️ **Spirit Form**
>
> | **-**       | **[Triggered action](../../../../rule/combat/triggered-action.md)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** An enemy moves within 2 squares of Psyche.
>
> **Effect:** Psyche moves up to 5 squares, and has damage immunity 5 and ignores [difficult terrain](../../../../movement/difficult-terrain.md) during this movement. The first time she moves through any creature during this movement, that creature takes 5 corruption damage.

> ❗️ **Vengeance for the Slain**
>
> | **Ranged**       | **Free [triggered action](../../../../rule/combat/triggered-action.md)** |
> |------------------|--------------------------:|
> | **📏 Ranged 10** |          **🎯 One enemy** |
>
> **Trigger:** A war dog within distance is made [winded](../../../../rule/health/winded.md) or reduced to 0 [Stamina](../../../../rule/health/stamina.md).
>
> **Effect:** The target loses all their [surges](../../../../rule/resource/surge.md) and takes 5 corruption damage.
>
> **1 [Malice](../../../../rule/monster/malice.md):** The target also takes a bane on their next strike.

> ⭐️ **Immortal Soul**
>
> When Psyche is reduced to 0 [Stamina](../../../../rule/health/stamina.md), her spirit surrounds the nearest war dog, who has damage immunity 2, deals an extra 5 damage on strikes, and can use the following Immortal Flare maneuver until the end of the encounter. That war dog also gains the Immortal Soul trait, and transfers this effect to the nearest war dog when they die.

> 🏹 **Immortal Flare**
>
> | **Magic, Ranged** |                  **[Maneuver](../../../../rule/combat/turn.md)** |
> |-------------------|------------------------------:|
> | **📏 Ranged 10**  | **🎯 One creature or object** |
>
> **Effect:** The target takes 10 psychic damage.
