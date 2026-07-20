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
      name: Grab and Bite
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [grabbed](../../../condition/grabbed.md)
            low: 7 damage; M < WEAK [grabbed](../../../condition/grabbed.md)
            mid: 11 damage; M < AVERAGE [grabbed](../../../condition/grabbed.md)
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Death to Death
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 17 corruption damage; P < STRONG [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 8 corruption damage; P < WEAK [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 13 corruption damage; P < AVERAGE [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: Before making the [strike](../../../rule/combat/strike.md), the servitor can [teleport](../../../movement/teleport.md) up to 10 squares to a space containing a dead creature, then burst out of the creature's body.
      target: One creature
      usage: Maneuver
    - cost: Encounter
      distance: 2 burst
      icon: ❗️
      keywords:
        - Area
        - Magic
      level: 10
      name: Death Miasma
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 corruption damage
            low: 6 corruption damage
            mid: 10 corruption damage
      sections:
        - label: Trigger
          text: The servitor is reduced to 0 [Stamina](../../../rule/health/stamina.md).
        - label: Effect
          text: The servitor explodes.
      target: Each enemy in the area
      usage: Free triggered action
name: Undead Servitor Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/undead-servitor
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🗡 **Grab and Bite (Encounter)**
>
> | **Melee, Strike, Weapon** |     **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage; M < WEAK [grabbed](../../../condition/grabbed.md)
> - **12-16:** 11 damage; M < AVERAGE [grabbed](../../../condition/grabbed.md)
> - **17+:** 16 damage; M < STRONG [grabbed](../../../condition/grabbed.md)

########Level 7 Retainer Advancement Ability

> 🏹 **Death to Death (Encounter)**
>
> | **Magic, Ranged, Strike** |        **[Maneuver](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 corruption damage; P < WEAK [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 13 corruption damage; P < AVERAGE [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 17 corruption damage; P < STRONG [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
>
> **Effect:** Before making the [strike](../../../rule/combat/strike.md), the servitor can [teleport](../../../movement/teleport.md) up to 10 squares to a space containing a dead creature, then burst out of the creature's body.

> **Level 10 Retainer Advancement Ability**

> ❗️ **Death Miasma (Encounter)**
>
> | **Area, Magic** |     **Free [triggered action](../../../rule/combat/triggered-action.md)** |
> |-----------------|------------------------------:|
> | **📏 2 burst**  | **🎯 Each enemy in the area** |
>
> **Trigger:** The servitor is reduced to 0 [Stamina](../../../rule/health/stamina.md).
>
> **Effect:** The servitor explodes.
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 corruption damage
> - **12-16:** 10 corruption damage
> - **17+:** 14 corruption damage
