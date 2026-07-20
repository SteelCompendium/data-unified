---
agility: 1
ev: "36"
free_strike: 5
intuition: 1
keywords:
    - Arixx
    - Beast
level: 1
might: 3
movement: Burrow
name: Arixx
organization: Solo
presence: -4
reason: -3
scc: mcdm.monsters.v1/monster.arixx.statblock/arixx
size: "2"
speed: 5
stability: 2
stamina: "200"
type: statblock
---

|   Arixx, Beast    |           -            |      Level 1       |         Solo          |        EV 36         |
|:-----------------:|:----------------------:|:------------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |     **5**<br>Speed     | **200**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **Burrow**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+3**<br>Might  |   **+1**<br>Agility    |  **-3**<br>Reason  |  **+1**<br>Intuition  |  **-4**<br>Presence  |

> ☠️ **Solo Monster**
>
> **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the arixx can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
>
> **Solo Turns:** The arixx can take two turns each round. They can't take turns consecutively.

> ⭐️ **Earthwalk**
>
> [Difficult terrain](../../../movement/difficult-terrain.md) composed of earth or loose rock doesn't cost the arixx extra movement.

> ⭐️ **Soft Underbelly**
>
> A [prone](../../../condition/prone.md) creature making a melee strike against the arixx has a double [edge](../../../rule/dice/edge.md) on the strike instead of taking a [bane](../../../rule/dice/bane.md).

> 🗡 **Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|------------------------------:|
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; [grabbed](../../../condition/grabbed.md)
> - **12-16:** 13 damage; [grabbed](../../../condition/grabbed.md)
> - **17+:** 16 damage; [grabbed](../../../condition/grabbed.md)
>
> **Effect:** A size 1 target [grabbed](../../../condition/grabbed.md) this way takes 3 acid damage at the start of each of their turns.

> 🗡 **Claw Swing**
>
> | **Melee, Strike, Weapon** |                 **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 damage; A < 1 [grabbed](../../../condition/grabbed.md)
> - **12-16:** 8 damage; A < 2 [grabbed](../../../condition/grabbed.md)
> - **17+:** 11 damage; A < 3 [grabbed](../../../condition/grabbed.md)
>
> **Effect:** The arixx can vertically [slide](../../../movement/forced-movement.md) each [grabbed](../../../condition/grabbed.md) target up to 3 squares.

> 🏹 **Spitfire**
>
> | **Ranged, Strike, Weapon** |                 **[Main action](../../../rule/combat/turn.md)** |
> |----------------------------|--------------------------------:|
> | **📏 Ranged 10**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 4 acid damage
> - **12-16:** 6 acid damage
> - **17+:** 7 acid damage; [prone](../../../condition/prone.md)
>
> **Effect:** The ground beneath each target is covered in burning acid until the end of the encounter. Any enemy who enters an affected space for the first time in a round or starts their turn there takes 2 acid damage.

> ❇️ **Dirt Devil (3 Malice)**
>
> | **Area**       |               **[Main action](../../../rule/combat/turn.md)** |
> |----------------|------------------------------:|
> | **📏 3 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage; [push](../../../movement/forced-movement.md) 2
> - **17+:** 7 damage; [push](../../../movement/forced-movement.md) 4
>
> **Effect:** The arixx flings rocks and debris to fill the area, and has a double [edge](../../../rule/dice/edge.md) on the power roll if they started their turn underground. The area is [difficult terrain](../../../movement/difficult-terrain.md).

> ❇️ **Dust Cloud**
>
> | **Area**       |   **[Maneuver](../../../rule/combat/turn.md)** |
> |----------------|---------------:|
> | **📏 1 burst** | **🎯 Special** |
>
> **Effect:** The arixx kicks up dust to fill the area until the start of their next turn, then moves up to their speed. Any enemy in the area or who targets a creature in the area takes a [bane](../../../rule/dice/bane.md) on power rolls.

> ❗️ **Skitter**
>
> | **-**       | **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The arixx takes damage.
>
> **Effect:** The arixx halves the damage and [shifts](../../../movement/shifting.md) up to 3 squares after the triggering effect resolves.

> ☠️ **Acid Spew (Villain Action 1)**
>
> | **Area, Weapon**            |                                       **-** |
> |-----------------------------|--------------------------------------------:|
> | **📏 10 x 2 line within 1** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 acid damage
> - **12-16:** 8 acid damage
> - **17+:** 11 acid damage
>
> **Effect:** The ground in the area is covered in a puddle of acid until the end of the encounter. Any enemy who enters the area for the first time in a round or starts their turn there takes 2 acid damage.

> ☠️ **Sinkhole (Villain Action 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The arixx [shifts](../../../movement/shifting.md) up to their speed. If they end this shift above ground and within 2 squares of a creature, they use Bite against the creature and can then use the Dig maneuver.

> ☠️ **Acid and Claws (Villain Action 3)**
>
> | **Area, Weapon**  |                            **-** |
> |-------------------|---------------------------------:|
> | **📏 2 burst**    | **🎯 Each creature in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 acid damage; M < 1 [weakened](../../../condition/weakened.md) (save ends)
> - **12-16:** 8 acid damage; M < 2 [weakened](../../../condition/weakened.md) (save ends)
> - **17+:** 11 acid damage; M < 3 [weakened](../../../condition/weakened.md) (save ends)
