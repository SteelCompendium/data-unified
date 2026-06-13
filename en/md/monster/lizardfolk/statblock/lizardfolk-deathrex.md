---
agility: 2
ev: "12"
free_strike: 4
intuition: 1
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
> - **≤11:** 7 damage; [pull](scc:mcdm.heroes.v1/movement/forced-movement) 1; A < 1 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 10 damage; [pull](scc:mcdm.heroes.v1/movement/forced-movement) 1; A < 2 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 12 damage; [pull](scc:mcdm.heroes.v1/movement/forced-movement) 2; A < 3 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **1 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** One target [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the deathrex is [grabbed](scc:mcdm.heroes.v1/condition/grabbed) in the deathrex's mouth.

> 🗡 **Death Roll (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |                       **Main action** |
> |---------------------------|--------------------------------------:|
> | **📏 Melee 1**            | **🎯 One grabbed creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; M < 1 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
> - **12-16:** 12 damage; M < 2 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 15 damage; M < 3 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
>
> **Effect:** The target is no longer [grabbed](scc:mcdm.heroes.v1/condition/grabbed) by the deathrex, and the deathrex [slides](scc:mcdm.heroes.v1/movement/forced-movement) them up to 5 squares.

> 👤 **Trundle**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The deathrex moves up to their speed. They can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each creature who makes an opportunity attack against them during this movement.

> ❗️ **Swat the Fly**
>
> | **Melee**      |                     **Triggered action** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance moves or [shifts](scc:mcdm.heroes.v1/movement/shifting) away from the deathrex.
>
> **Effect:** The deathrex [slides](scc:mcdm.heroes.v1/movement/forced-movement) the target up to 5 squares.

> ⭐️ **Rex Reptilian Escape**
>
> While the deathrex has a tail, whenever they are affected by an effect that can be ended by a [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their turn, they can lose their tail to immediately end that effect, then [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares.

> ☠️ **Snack Attack ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area**        |                                 **-** |
> |-----------------|--------------------------------------:|
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target moves up to their speed and can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike). Each target gains temporary [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to the damage they deal.

> ☠️ **Shed Some Skin ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The deathrex [shifts](scc:mcdm.heroes.v1/movement/shifting) up to their speed, leaving behind a shed skin duplicate in the space they started in. The duplicate acts on the deathrex's turn and has the deathrex's characteristics, but has 10 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) and no [villain actions](scc:mcdm.monsters.v1/rule.monster/villain-action).

> ☠️ **Thresher Thrasher ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area**        |                                 **-** |
> |-----------------|--------------------------------------:|
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target moves up to their speed. Until the end of the encounter, whenever a creature comes [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to a target or starts their turn there, the target can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
