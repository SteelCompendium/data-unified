---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Tackle
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; [push](../../../movement/forced-movement.md) 4
            low: 5 damage; [push](../../../movement/forced-movement.md) 1
            mid: 9 damage; [push](../../../movement/forced-movement.md) 2
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Meet You There
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 15 damage
            low: 7 damage
            mid: 10 damage
      sections:
        - label: Effect
          text: Before or after the strike, the retainer and their mentor can each [shift](../../../movement/shifting.md) up to their speed.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Nab and Stab
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; one target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
            low: 11 damage; one target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
            mid: 16 damage; one target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
      sections:
        - label: Effect
          text: The retainer [shifts](../../../movement/shifting.md) up to 2 squares, and can move a creature [grabbed](../../../condition/grabbed.md) using this ability with them.
      target: Each creature in the area
      usage: Main action
name: Harrier Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/harrier
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 🗡 **Tackle (Encounter)**
>
> **Power Roll + highest characteristic:**
>
> | **Charge, Melee, Strike, Weapon** |  **[Main action](../../../rule/combat/turn.md)** |
> |-----------------------------------|-----------------:|
> | **📏 Melee 1**                    | **🎯 One enemy** |
>
> - **≤11:** 5 damage; [push](../../../movement/forced-movement.md) 1
> - **12-16:** 9 damage; [push](../../../movement/forced-movement.md) 2
> - **17+:** 12 damage; [push](../../../movement/forced-movement.md) 4

> **Level 7 Role Advancement Ability**

> 🗡 **Meet You There (Encounter)**
>
> | **Melee, Strike, Weapon** |     **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage
> - **12-16:** 10 damage
> - **17+:** 15 damage
>
> **Effect:** Before or after the strike, the retainer and their mentor can each [shift](../../../movement/shifting.md) up to their speed.

> **Level 10 Role Advancement Ability**

> ❇️ **Nab and Stab (Encounter)**
>
> | **Area, Weapon** |                  **[Main action](../../../rule/combat/turn.md)** |
> |------------------|---------------------------------:|
> | **📏 1 burst**   | **🎯 Each creature in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 11 damage; one target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
> - **12-16:** 16 damage; one target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
> - **17+:** 21 damage; one target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
>
> **Effect:** The retainer [shifts](../../../movement/shifting.md) up to 2 squares, and can move a creature [grabbed](../../../condition/grabbed.md) using this ability with them.
