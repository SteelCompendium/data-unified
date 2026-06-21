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
      name: Leaping Attack
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; M < STRONG, [prone](../../../condition/prone.md)
            low: 5 damage; M < WEAK, [prone](../../../condition/prone.md)
            mid: 9 damage; M < AVERAGE, [prone](../../../condition/prone.md)
      sections:
        - label: Effect
          text: The hopper can jump up to their speed in a straight line before the [strike](../../../rule/combat/strike.md) without provoking [opportunity attacks](../../../rule/combat/opportunity-attack.md). If they jump 2 or more squares this way, they gain 1 [surge](../../../rule/resource/surge.md).
      target: One creature or object
      usage: Main action
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 7
      name: Three-Poison Dart
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 poison damage; M < STRONG, [dazed](../../../condition/dazed.md), [slowed](../../../condition/slowed.md), and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 5 poison damage; M < WEAK, [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 9 poison damage; M < AVERAGE, [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Melee 5
      icon: ❗️
      keywords:
        - Melee
      level: 10
      name: Trip of the Tongue
      sections:
        - label: Trigger
          text: A creature moves within distance.
        - label: Effect
          text: If the target has M < AVERAGE, their movement ends, they are knocked [prone](../../../condition/prone.md), and one ally within distance gains 2 [surges](../../../rule/resource/surge.md).
      target: One creature or object
      usage: Triggered action
name: Angulotl Hopper Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/angulotl-hopper
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🗡 **Leaping Attack (Encounter)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 damage; M < WEAK, [prone](../../../condition/prone.md)
> - **12-16:** 9 damage; M < AVERAGE, [prone](../../../condition/prone.md)
> - **17+:** 12 damage; M < STRONG, [prone](../../../condition/prone.md)
>
> **Effect:** The hopper can jump up to their speed in a straight line before the [strike](../../../rule/combat/strike.md) without provoking [opportunity attacks](../../../rule/combat/opportunity-attack.md). If they jump 2 or more squares this way, they gain 1 [surge](../../../rule/resource/surge.md).

> **Level 7 Retainer Advancement Ability**

> 🏹 **Three-Poison Dart (Encounter)**
>
> | **Ranged, Strike, Weapon** |     **Main action** |
> |----------------------------|--------------------:|
> | **📏 Ranged 5**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 poison damage; M < WEAK, [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 9 poison damage; M < AVERAGE, [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 12 poison damage; M < STRONG, [dazed](../../../condition/dazed.md), [slowed](../../../condition/slowed.md), and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)

> **Level 10 Retainer Advancement Ability**

> ❗️ **Trip of the Tongue (Encounter)**
>
> | **Melee**      |          **Triggered action** |
> |----------------|------------------------------:|
> | **📏 Melee 5** | **🎯 One creature or object** |
>
> **Trigger:** A creature moves within distance.
>
> **Effect:** If the target has M < AVERAGE, their movement ends, they are knocked [prone](../../../condition/prone.md), and one ally within distance gains 2 [surges](../../../rule/resource/surge.md).
