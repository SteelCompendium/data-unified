---
features:
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 7
      name: Slow-Poison Needle
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 poison damage; [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 8 poison damage; [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 12 poison damage; [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: The slow-poison needle is initially painless, with the damage and effect delayed until the start of the target's next turn. If the shade is hidden, using this ability doesn't cause them to be revealed.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 10
      name: Shadow Dagger
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 23 poison damage; the target has shadowed vision (save ends)
            low: 12 poison damage; the target has shadowed vision (save ends)
            mid: 17 poison damage; the target has shadowed vision (save ends)
      sections:
        - label: Effect
          text: While a creature has shadowed vision, all creatures have concealment from them.
      target: One creature
      usage: Main action
name: Shadow Elf Shade Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/shadow-elf-shade
type: featureblock
---

> **Level 7 Retainer Advancement Ability**

> 🏹 **Slow-Poison Needle (Encounter)**
>
> | **Ranged, Strike, Weapon** |     **[Main action](../../../rule/combat/turn.md)** |
> |----------------------------|--------------------:|
> | **📏 Ranged 5**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 poison damage; [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 12 poison damage; [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 16 poison damage; [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
>
> **Effect:** The slow-poison needle is initially painless, with the damage and effect delayed until the start of the target's next turn. If the shade is hidden, using this ability doesn't cause them to be revealed.

> **Level 10 Retainer Advancement Ability**

> 🗡 **Shadow Dagger (Encounter)**
>
> | **Melee, Strike, Weapon** |     **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 12 poison damage; the target has shadowed vision (save ends)
> - **12-16:** 17 poison damage; the target has shadowed vision (save ends)
> - **17+:** 23 poison damage; the target has shadowed vision (save ends)
>
> **Effect:** While a creature has shadowed vision, all creatures have concealment from them.
