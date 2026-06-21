---
agility: 2
ev: "12"
file_basename: lizardfolk-deathrex
file_dpath: monster/lizardfolk/statblock
free_strike: 4
intuition: 1
item_id: lizardfolk-deathrex
item_name: Lizardfolk Deathrex
keywords:
    - Humanoid
    - Lizardfolk
level: 1
might: 3
movement: Climb, swim
name: Lizardfolk Deathrex
organization: Leader
presence: 2
reason: 0
scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-deathrex
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "80"
type: statblock
---

| Humanoid, Lizardfolk |              -              |      Level 1      |        Leader         |        EV 12         |
|:--------------------:|:---------------------------:|:-----------------:|:---------------------:|:--------------------:|
|    **2**<br>Size     |       **5**<br>Speed        | **80**<br>Stamina |  **2**<br>Stability   | **4**<br>Free Strike |
|  **-**<br>Immunity   | **Climb, swim**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|   **+3**<br>Might    |      **+2**<br>Agility      |  **0**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Ripper Spear (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 damage; [pull](../../../movement/forced-movement.md) 1; A < 1 [bleeding](../../../condition/bleeding.md) (save ends)
> - **12-16:** 10 damage; [pull](../../../movement/forced-movement.md) 1; A < 2 [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 12 damage; [pull](../../../movement/forced-movement.md) 2; A < 3 [bleeding](../../../condition/bleeding.md) (save ends)
>
> **1 [Malice](../../../rule/monster/malice.md):** One target [adjacent](../../../rule/combat/adjacent.md) to the deathrex is [grabbed](../../../condition/grabbed.md) in the deathrex's mouth.

> 🗡 **Death Roll (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Melee, Strike, Weapon** |                       **Main action** |
> |---------------------------|--------------------------------------:|
> | **📏 Melee 1**            | **🎯 One grabbed creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; M < 1 [dazed](../../../condition/dazed.md) (save ends)
> - **12-16:** 12 damage; M < 2 [dazed](../../../condition/dazed.md) (save ends)
> - **17+:** 15 damage; M < 3 [dazed](../../../condition/dazed.md) (save ends)
>
> **Effect:** The target is no longer [grabbed](../../../condition/grabbed.md) by the deathrex, and the deathrex [slides](../../../movement/forced-movement.md) them up to 5 squares.

> 👤 **Trundle**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The deathrex moves up to their speed. They can make a [free strike](../../../feature/common/main-actions/free-strike.md) against each creature who makes an opportunity attack against them during this movement.

> ❗️ **Swat the Fly**
>
> | **Melee**      |                     **Triggered action** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance moves or [shifts](../../../movement/shifting.md) away from the deathrex.
>
> **Effect:** The deathrex [slides](../../../movement/forced-movement.md) the target up to 5 squares.

> ⭐️ **Rex Reptilian Escape**
>
> While the deathrex has a tail, whenever they are affected by an effect that can be ended by a [saving throw](../../../rule/general/saving-throw.md) or that ends at the end of their turn, they can lose their tail to immediately end that effect, then [shift](../../../movement/shifting.md) up to 2 squares.

> ☠️ **Snack Attack ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area**        |                                 **-** |
> |-----------------|--------------------------------------:|
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target moves up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md). Each target gains temporary [Stamina](../../../rule/health/stamina.md) equal to the damage they deal.

> ☠️ **Shed Some Skin ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The deathrex [shifts](../../../movement/shifting.md) up to their speed, leaving behind a shed skin duplicate in the space they started in. The duplicate acts on the deathrex's turn and has the deathrex's characteristics, but has 10 [Stamina](../../../rule/health/stamina.md) and no [villain actions](../../../rule/monster/villain-action.md).

> ☠️ **Thresher Thrasher ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **Area**        |                                 **-** |
> |-----------------|--------------------------------------:|
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target moves up to their speed. Until the end of the encounter, whenever a creature comes [adjacent](../../../rule/combat/adjacent.md) to a target or starts their turn there, the target can make a [free strike](../../../feature/common/main-actions/free-strike.md) against them.
