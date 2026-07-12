---
features:
    - cost: Encounter
      distance: Ranged 15
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 4
      name: Snipe
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      sections:
        - label: Effect
          text: If the arrowswift is hidden when they use this ability, they gain 2 [surges](../../../rule/resource/surge.md) that can be used immediately.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Self
      icon: "\U0001F464"
      level: 7
      name: Magic Arrows
      sections:
        - label: Effect
          text: Until the end of the encounter, whenever the arrowswift makes a ranged [strike](../../../rule/combat/strike.md), the [strike](../../../rule/combat/strike.md) gains an edge and the arrowswift gains 1 [surge](../../../rule/resource/surge.md) that must be used immediately. While the arrowswift's mentor is [adjacent](../../../rule/combat/adjacent.md) to them, the mentor also gains this benefit.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: Ranged 15
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Double Shot
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 23 damage
            low: 12 damage
            mid: 17 damage
      target: Two creatures or objects
      usage: Main action
file_basename: wode-elf-arrowswift
file_dpath: monster/retainer/advancement-features
item_id: wode-elf-arrowswift
item_name: Wode Elf Arrowswift Advancement Features
name: Wode Elf Arrowswift Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/wode-elf-arrowswift
source: mcdm.monsters.v1
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🏹 **Snipe (Encounter)**
>
> | **Ranged, Strike, Weapon** |     **Main action** |
> |----------------------------|--------------------:|
> | **📏 Ranged 15**           | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage
> - **17+:** 16 damage
>
> **Effect:** If the arrowswift is hidden when they use this ability, they gain 2 [surges](../../../rule/resource/surge.md) that can be used immediately.

> **Level 7 Retainer Advancement Ability**

> 👤 **Magic Arrows (Encounter)**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Until the end of the encounter, whenever the arrowswift makes a ranged [strike](../../../rule/combat/strike.md), the [strike](../../../rule/combat/strike.md) gains an edge and the arrowswift gains 1 [surge](../../../rule/resource/surge.md) that must be used immediately. While the arrowswift's mentor is [adjacent](../../../rule/combat/adjacent.md) to them, the mentor also gains this benefit.

> **Level 10 Retainer Advancement Ability**

> 🏹 **Double Shot (Encounter)**
>
> | **Ranged, Strike, Weapon** |                 **Main action** |
> |----------------------------|--------------------------------:|
> | **📏 Ranged 15**           | **🎯 Two creatures or objects** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 12 damage
> - **12-16:** 17 damage
> - **17+:** 23 damage
