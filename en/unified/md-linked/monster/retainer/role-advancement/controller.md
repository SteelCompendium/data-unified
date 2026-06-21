---
features:
    - cost: Encounter
      distance: 3 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      level: 4
      name: Elemental Blast
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 10 damage; [push](../../../movement/forced-movement.md) 5
            low: 4 damage; [push](../../../movement/forced-movement.md) 2
            mid: 6 damage; [push](../../../movement/forced-movement.md) 3
      sections:
        - label: Effect
          text: 'When the retainer uses this ability, they can choose for it to deal one of the following damage types: acid, cold, fire, lightning, poison, or sonic.'
      target: Each creature in the area
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      level: 7
      name: Oil Slick
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 11 poison damage; M < STRONG [prone](../../../condition/prone.md)
            low: 5 poison damage; M < WEAK [prone](../../../condition/prone.md)
            mid: 8 poison damage; M < AVERAGE [prone](../../../condition/prone.md)
      sections:
        - label: Effect
          text: The area is [difficult terrain](../../../movement/difficult-terrain.md) for enemies. Any enemy has fire weakness 5 while in the area, and any enemy who ends their turn in the area and has no movement remaining falls [prone](../../../condition/prone.md).
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Shattering Shards
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      sections:
        - label: Special
          text: The target must be size 1M or smaller.
        - label: Effect
          text: The area within 2 squares of the target is [difficult terrain](../../../movement/difficult-terrain.md), and each enemy in the area takes the same damage the object took.
      target: One Object
      usage: Main action
name: Controller Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/controller
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 🔳 **Elemental Blast (Encounter)**
>
> | **Area, Magic, Ranged** |                  **Main action** |
> |-------------------------|---------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each creature in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 4 damage; [push](../../../movement/forced-movement.md) 2
> - **12-16:** 6 damage; [push](../../../movement/forced-movement.md) 3
> - **17+:** 10 damage; [push](../../../movement/forced-movement.md) 5
>
> **Effect:** When the retainer uses this ability, they can choose for it to deal one of the following damage types: acid, cold, fire, lightning, poison, or sonic.

> **Level 7 Role Advancement Ability**

> 🔳 **Oil Slick (Encounter)**
>
> | **Area, Ranged, Weapon** |               **Main action** |
> |--------------------------|------------------------------:|
> | **📏 3 cube within 10**  | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 poison damage; M < WEAK [prone](../../../condition/prone.md)
> - **12-16:** 8 poison damage; M < AVERAGE [prone](../../../condition/prone.md)
> - **17+:** 11 poison damage; M < STRONG [prone](../../../condition/prone.md)
>
> **Effect:** The area is [difficult terrain](../../../movement/difficult-terrain.md) for enemies. Any enemy has fire weakness 5 while in the area, and any enemy who ends their turn in the area and has no movement remaining falls [prone](../../../condition/prone.md).

> **Level 10 Role Advancement Ability**

> 🏹 **Shattering Shards (Encounter)**
>
> | **Ranged, Strike, Weapon** |   **Main action** |
> |----------------------------|------------------:|
> | **📏 Ranged 10**           | **🎯 One Object** |
>
> **Special:** The target must be size 1M or smaller.
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage
> - **17+:** 16 damage
>
> **Effect:** The area within 2 squares of the target is [difficult terrain](../../../movement/difficult-terrain.md), and each enemy in the area takes the same damage the object took.
