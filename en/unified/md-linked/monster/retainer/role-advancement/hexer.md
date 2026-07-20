---
features:
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Backfire Curse
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 7 corruption damage; the target is cursed (EoT)
            low: 2 corruption damage; the target is cursed (EoT)
            mid: 5 corruption damage; the target is cursed (EoT)
      sections:
        - label: Effect
          text: While the target is cursed this way, whenever they make a strike that targets only one creature, the retainer can use a free triggered action to choose a second target for the strike within its distance.
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Take Root
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; M < STRONG [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 5 damage; M < WEAK [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 9 damage; M < AVERAGE [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: While the target is [slowed](../../../condition/slowed.md) this way, if they end their turn without moving on that turn, they are no longer [slowed](../../../condition/slowed.md) and are [restrained](../../../condition/restrained.md) ([save](../../../rule/general/saving-throw.md) ends).
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 10
      name: Mazed
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; if the target has M < STRONG they are mazed (save ends)
            low: 7 damage; if the target has M < WEAK they are mazed (save ends)
            mid: 11 damage; if the target has M < AVERAGE they are mazed (save ends)
      sections:
        - label: Effect
          text: While mazed, the target is [dazed](../../../condition/dazed.md). Additionally, at the end of each of the mazed target's turns, the retainer can cause the target to move up to their speed in a straight line in a direction of the retainer's choice. This is not [forced movement](../../../movement/forced-movement.md), and the movement ends if it would cause the target to enter [difficult](../../../movement/difficult-terrain.md) or damaging terrain.
      target: One creature
      usage: Main action
name: Hexer Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/hexer
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 🏹 **Backfire Curse (Encounter)**
>
> | **Magic, Ranged, Strike** |  **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|-----------------:|
> | **📏 Ranged 10**          | **🎯 One enemy** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 2 corruption damage; the target is cursed (EoT)
> - **12-16:** 5 corruption damage; the target is cursed (EoT)
> - **17+:** 7 corruption damage; the target is cursed (EoT)
>
> **Effect:** While the target is cursed this way, whenever they make a strike that targets only one creature, the retainer can use a free triggered action to choose a second target for the strike within its distance.

## Level 7 Role Advancement Ability

>
> 🏹 **Take Root (Encounter)**
>
> | **Magic, Ranged, Strike** |     **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 damage; M < WEAK [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 9 damage; M < AVERAGE [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 12 damage; M < STRONG [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
>
> **Effect:** While the target is [slowed](../../../condition/slowed.md) this way, if they end their turn without moving on that turn, they are no longer [slowed](../../../condition/slowed.md) and are [restrained](../../../condition/restrained.md) ([save](../../../rule/general/saving-throw.md) ends).

> **Level 10 Role Advancement Ability**

> 🏹 **Mazed (Encounter)**
>
> | **Magic, Ranged, Strike** |     **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage; if the target has M < WEAK they are mazed (save ends)
> - **12-16:** 11 damage; if the target has M < AVERAGE they are mazed (save ends)
> - **17+:** 16 damage; if the target has M < STRONG they are mazed (save ends)
>
> **Effect:** While mazed, the target is [dazed](../../../condition/dazed.md). Additionally, at the end of each of the mazed target's turns, the retainer can cause the target to move up to their speed in a straight line in a direction of the retainer's choice. This is not [forced movement](../../../movement/forced-movement.md), and the movement ends if it would cause the target to enter [difficult](../../../movement/difficult-terrain.md) or damaging terrain.
