---
agility: 1
ev: "6"
free_strike: 4
intuition: 0
keywords:
    - Humanoid
    - Radenwight
level: 1
might: 2
movement: Climb
name: Radenwight Bruxer
organization: Platoon
presence: 1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-bruxer
size: 1L
speed: 5
stability: 2
stamina: "40"
type: statblock
---

| Humanoid, Radenwight |           -           |      Level 1      |     Platoon Brute     |         EV 6         |
|:--------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|    **1L**<br>Size    |    **5**<br>Speed     | **40**<br>Stamina |  **2**<br>Stability   | **4**<br>Free Strike |
|  **-**<br>Immunity   | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|   **+2**<br>Might    |   **+1**<br>Agility   | **-1**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence  |

> 🗡 **Lockjaw ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |               **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage; [grabbed](../../../condition/grabbed.md)
>
> **Effect:** A target [grabbed](../../../condition/grabbed.md) this way takes 2 damage at the start of each of the bruxer's turns.

> ❇️ **Flurry of Bites (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Weapon** |               **[Main action](../../../rule/combat/turn.md)** |
> |------------------|------------------------------:|
> | **📏 1 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; A < 0 [bleeding](../../../condition/bleeding.md) (save ends)
> - **12-16:** 5 damage; A < 1 [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 8 damage; A < 2 [bleeding](../../../condition/bleeding.md) (save ends)

> ❗️ **Ready Rodent**
>
> | **Melee, Weapon** | **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |-------------------|---------------------:|
> | **📏 Melee 1**    |  **🎯 One creature** |
>
> **Trigger:** An ally deals damage to the target.
>
> **Effect:** The bruxer makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target.

> ⭐️ **Lockdown**
>
> Any enemy who [shifts](../../../movement/shifting.md) [adjacent](../../../rule/combat/adjacent.md) to the bruxer has that shift end. Additionally, any enemy [adjacent](../../../rule/combat/adjacent.md) to the bruxer can't [shift](../../../movement/shifting.md).
