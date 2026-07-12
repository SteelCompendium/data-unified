---
features:
    - distance: Self
      icon: "\U0001F464"
      level: 4
      name: Big Windup
      sections:
        - label: Effect
          text: Until the start of the retainer's next turn, strikes made against the retainer gain an edge. At the start of the retainer's next turn, they gain 2 [surges](../../../rule/resource/surge.md), and any ability they use before the end of their turn that [force moves](../../../movement/forced-movement.md) a creature can move that creature 2 additional squares.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Overhand Swat
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [push](../../../movement/forced-movement.md) 3; M < STRONG [prone](../../../condition/prone.md)
            low: 8 damage
            mid: 13 damage; [push](../../../movement/forced-movement.md) 2
      sections:
        - label: Effect
          text: If the target ends any [forced movement](../../../movement/forced-movement.md) from this ability in a square [adjacent](../../../rule/combat/adjacent.md) to the retainer's mentor, the mentor can make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against them.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Dizzying Sweep
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 20 damage; [push](../../../movement/forced-movement.md) 4
            low: 10 damage; [push](../../../movement/forced-movement.md) 1
            mid: 14 damage; [push](../../../movement/forced-movement.md) 2
      sections:
        - label: Effect
          text: The retainer is [dazed](../../../condition/dazed.md) until the end of their next turn.
      target: Each creature in the area
      usage: Main action
file_basename: brute
file_dpath: monster/retainer/role-advancement
item_id: brute
item_name: Brute Abilities
name: Brute Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/brute
source: mcdm.monsters.v1
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 👤 **Big Windup**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Until the start of the retainer's next turn, strikes made against the retainer gain an edge. At the start of the retainer's next turn, they gain 2 [surges](../../../rule/resource/surge.md), and any ability they use before the end of their turn that [force moves](../../../movement/forced-movement.md) a creature can move that creature 2 additional squares.

> **Level 7 Role Advancement Ability**

> 🗡 **Overhand Swat (Encounter)**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage
> - **12-16:** 13 damage; [push](../../../movement/forced-movement.md) 2
> - **17+:** 16 damage; [push](../../../movement/forced-movement.md) 3; M < STRONG [prone](../../../condition/prone.md)
>
> **Effect:** If the target ends any [forced movement](../../../movement/forced-movement.md) from this ability in a square [adjacent](../../../rule/combat/adjacent.md) to the retainer's mentor, the mentor can make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against them.

> **Level 10 Role Advancement Ability**

> ❇️ **Dizzying Sweep (Encounter)**
>
> | **Area, Weapon** |                  **Main action** |
> |------------------|---------------------------------:|
> | **📏 1 burst**   | **🎯 Each creature in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 10 damage; [push](../../../movement/forced-movement.md) 1
> - **12-16:** 14 damage; [push](../../../movement/forced-movement.md) 2
> - **17+:** 20 damage; [push](../../../movement/forced-movement.md) 4
>
> **Effect:** The retainer is [dazed](../../../condition/dazed.md) until the end of their next turn.
