---
agility: 1
ev: "44"
file_basename: multivok-chief
file_dpath: monster/valok/statblock
free_strike: 9
intuition: 1
item_id: multivok-chief
item_name: Multivok Chief
keywords:
    - Construct
    - Multivok
    - Soulless
    - Valok
level: 9
might: 4
name: Multivok Chief
organization: Elite
presence: -3
reason: -2
role: Support
scc: mcdm.monsters.v1/monster.valok.statblock/multivok-chief
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "220"
type: statblock
---

| Construct, Multivok, Soulless, Valok |         -         |      Level 9       |     Elite Support     |        EV 44         |
|:------------------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|            **1L**<br>Size            |  **5**<br>Speed   | **220**<br>Stamina |  **3**<br>Stability   | **9**<br>Free Strike |
|          **-**<br>Immunity           | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|           **+4**<br>Might            | **+1**<br>Agility |  **-2**<br>Reason  |  **+1**<br>Intuition  |  **-3**<br>Presence  |

> 🗡 **Pneumatic Punch ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 13 damage; [push](../../../movement/forced-movement.md) 3
> - **12-16:** 18 damage; [push](../../../movement/forced-movement.md) 5
> - **17+:** 22 damage; [push](../../../movement/forced-movement.md) 8

> 🏹 **Targeting Beam (3 Malice)**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 10**           | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 15 damage; A < 2 [slowed](../../../condition/slowed.md) (save ends)
> - **12-16:** 21 damage; A < 3 [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 26 damage; A < 4 [slowed](../../../condition/slowed.md) (save ends)
>
> **Effect:** This damage can't be reduced in any way. While a target is [slowed](../../../condition/slowed.md) this way, any strike against them has a double edge.

> 🏹 **Chief's Command**
>
> | **Ranged**      |    **Maneuver** |
> |-----------------|----------------:|
> | **📏 Ranged 5** | **🎯 One ally** |
>
> **Effect:** The target [shifts](../../../movement/shifting.md) up to their speed and can use a main action.

> ❗️ **Quick Shield**
>
> | **Ranged**       |           **[Triggered Action](../../../rule/combat/triggered-action.md)** |
> |------------------|-------------------------------:|
> | **📏 Ranged 10** | **🎯 The triggering creature** |
>
> **Trigger:** The chief or an ally within distance is subject to an effect that can be ended by a [saving throw](../../../rule/general/saving-throw.md) or that ends at the end of their turn.
>
> **Effect:** The target gains 15 temporary [Stamina](../../../rule/health/stamina.md). Each time this triggered action is used, the amount of temporary [Stamina](../../../rule/health/stamina.md) received decreases by 3 (to a minimum of 0).

> ⭐️ **Multivok Maintenance**
>
> At the start of the chief's turn, each servok within 2 squares of them regains 15 [Stamina](../../../rule/health/stamina.md).

> ⭐️ **Crafted to Perfection**
>
> The chief's shape can't be changed by any external effect.

> ⭐️ **Valiar Might**
>
> While the chief isn't [bleeding](../../../condition/bleeding.md), [weakened](../../../condition/weakened.md), or [winded](../../../rule/health/winded.md), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
