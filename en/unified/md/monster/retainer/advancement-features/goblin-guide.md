---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Weaving Knives
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage
            low: 5 damage
            mid: 9 damage
      sections:
        - label: Effect
          text: The guide [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed before and after the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
      target: One creature or object
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Sneak and Stab
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; the guide and their mentor can each move up to their speed, then attempt to [hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide)
            low: 8 damage
            mid: 12 damage; the guide and their mentor can each move up to their speed
      sections:
        - label: Effect
          text: If the guide is hidden from the target, this ability has a double edge.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Special
      icon: "\U0001F300"
      keywords:
        - '-'
      level: 10
      name: Poison Blade
      sections:
        - label: Effect
          text: The guide applies poison to their weapon. The next time the guide obtains a tier 2 or tier 3 outcome on a weapon [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals an extra 10 poison damage, and if the target has M < AVERAGE, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends). If the guide is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to their mentor when they use Poison Blade, they apply poison to the mentor's weapon in the same way.
      target: Special
      usage: Main action
name: Goblin Guide Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/goblin-guide
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🗡 **Weaving Knives (Encounter)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage
>
> **Effect:** The guide [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed before and after the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).

> **Level 7 Retainer Advancement Ability**

> 🗡 **Sneak and Stab (Encounter)**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage
> - **12-16:** 12 damage; the guide and their mentor can each move up to their speed
> - **17+:** 16 damage; the guide and their mentor can each move up to their speed, then attempt to [hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide)
>
> **Effect:** If the guide is hidden from the target, this ability has a double edge.

> **Level 10 Retainer Advancement Ability**

> 🌀 **Poison Blade (Encounter)**
>
> | **-**          | **Main action** |
> |----------------|----------------:|
> | **📏 Special** |  **🎯 Special** |
>
> **Effect:** The guide applies poison to their weapon. The next time the guide obtains a tier 2 or tier 3 outcome on a weapon [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals an extra 10 poison damage, and if the target has M < AVERAGE, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends). If the guide is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to their mentor when they use Poison Blade, they apply poison to the mentor's weapon in the same way.
