---
features:
    - distance: Self
      icon: "\U0001F464"
      level: 4
      name: Boost
      sections:
        - label: Effect
          text: If the sidekick's mentor moves [adjacent](../../../rule/combat/adjacent.md) to the sidekick at any point during the mentor's turn, the mentor gains a +1 bonus to speed and can automatically climb at full speed while moving until the end of their turn.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: 3 cube within 3
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
      level: 7
      name: Bug Bag
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 13 poison damage; M < STRONG [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 6 poison damage; M < WEAK [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 9 poison damage; M < AVERAGE [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each creature in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      level: 10
      name: Triumphant Squeak
      sections:
        - label: Effect
          text: Each target can spend a [Recovery](../../../rule/health/recoveries.md), and ends the [dazed](../../../condition/dazed.md), [frightened](../../../condition/frightened.md), and [weakened](../../../condition/weakened.md) conditions on themself.
      target: Self and each ally
      usage: Maneuver
name: Radenwight Sidekick Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/radenwight-sidekick
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 👤 **Boost**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** If the sidekick's mentor moves [adjacent](../../../rule/combat/adjacent.md) to the sidekick at any point during the mentor's turn, the mentor gains a +1 bonus to speed and can automatically climb at full speed while moving until the end of their turn.

> **Level 7 Retainer Advancement Ability**

> 🔳 **Bug Bag (Encounter)**
>
> | **Area, Ranged**       |                  **Main action** |
> |------------------------|---------------------------------:|
> | **📏 3 cube within 3** | **🎯 Each creature in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 poison damage; M < WEAK [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 9 poison damage; M < AVERAGE [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 13 poison damage; M < STRONG [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)

> **Level 10 Retainer Advancement Ability**

> 🏹 **Triumphant Squeak (Encounter)**
>
> | **Ranged** | **Maneuver** |
> | --- | ---:|
> | **📏 Ranged 10** | **🎯 Self and each ally** |
>
> **Effect:** Each target can spend a [Recovery](../../../rule/health/recoveries.md), and ends the [dazed](../../../condition/dazed.md), [frightened](../../../condition/frightened.md), and [weakened](../../../condition/weakened.md) conditions on themself.
