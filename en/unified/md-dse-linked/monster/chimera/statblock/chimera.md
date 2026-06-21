---
agility: 2
ev: "60"
file_basename: chimera
file_dpath: monster/chimera/statblock
free_strike: 6
immunities:
    - Fire 6
intuition: 1
item_id: chimera
item_name: Chimera
keywords:
    - Beast
    - Chimera
level: 3
might: 3
movement: Fly
name: Chimera
organization: Solo
presence: 0
reason: -2
scc: mcdm.monsters.v1/monster.chimera.statblock/chimera
size: "2"
source: mcdm.monsters.v1
speed: 10
stability: 1
stamina: "300"
type: statblock
---

|     Beast, Chimera     |          -          |      Level 3       |         Solo          |        EV 60         |
|:----------------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|
|     **2**<br>Size      |   **10**<br>Speed   | **300**<br>Stamina |  **1**<br>Stability   | **6**<br>Free Strike |
| **Fire 6**<br>Immunity | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+3**<br>Might     |  **+2**<br>Agility  |  **-2**<br>Reason  |  **+1**<br>Intuition  |  **+0**<br>Presence  |

> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the chimera can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
>
> **Solo Turns:** The chimera can take two turns each round. They can't take turns consecutively.

> ⭐️ **Volant**
>
> When the chimera makes a creature [winded](../../../rule/health/winded.md) or reduces them to 0 [Stamina](../../../rule/health/stamina.md), they can move their speed toward an enemy.

> 🗡 **Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage
> - **12-16:** 13 damage
> - **17+:** 16 damage
>
> **Effect:** This strike deals an extra 3 damage if it gains an [edge](../../../rule/dice/edge.md) or has a double edge.

> 🔳 **Dragon's Eruption (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Magic, Ranged** |               **Main action** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 3 fire damage; A < 1 3 fire damage
> - **12-16:** 5 fire damage; A < 2 5 fire damage
> - **17+:** 7 fire damage; A < 3 7 fire damage

> ❇️ **Roar (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 4 psychic damage
> - **12-16:** 8 psychic damage; I < 2 [frightened](../../../condition/frightened.md) (save ends)
> - **17+:** 10 psychic damage; I < 3 [frightened](../../../condition/frightened.md) (save ends)

> 🗡 **Lion's Toss**
>
> | **Melee, Weapon** |                  **Maneuver** |
> |-------------------|------------------------------:|
> | **📏 Melee 2**    | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** Vertical push 2
> - **12-16:** Vertical push 3
> - **17+:** Vertical push 5

> ❗️ **Ram's Defiance**
>
> | **Melee, Strike, Weapon** |           **Triggered action** |
> |---------------------------|-------------------------------:|
> | **📏 Melee 2**            | **🎯 The triggering creature** |
>
> **Trigger:** A creature makes a strike against the chimera and obtains a tier 1 outcome.
>
> **Effect:** The chimera [shifts](../../../movement/shifting.md) up to 5 squares. If they end this shift within distance of the target, make a power roll.
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage; M < 1 [slowed](../../../condition/slowed.md) (save ends)
> - **12-16:** 8 damage; [prone](../../../condition/prone.md); M < 2 [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 10 damage; [prone](../../../condition/prone.md); M < 3 [slowed](../../../condition/slowed.md) (save ends)

> ☠️ **Overture of Destruction (Villain Action 1)**
>
> | **Area**       |                         **-** |
> |----------------|------------------------------:|
> | **📏 1 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** The chimera can use Bite and Lion's Toss against each target.

> ☠️ **Fire Solo (Villain Action 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The chimera uses Dragon's Eruption and Roar without spending [Malice](../../../rule/monster/malice.md).

> ☠️ **Chorus of Destruction (Villain Action 3)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The chimera uses Roar, then [shifts](../../../movement/shifting.md) up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md) against each enemy who comes [adjacent](../../../rule/combat/adjacent.md) to them during the shift. When the chimera ends this shift, they use Dragon's Eruption. The use of these abilities as part of this [villain action](../../../rule/monster/villain-action.md) costs no [Malice](../../../rule/monster/malice.md).
