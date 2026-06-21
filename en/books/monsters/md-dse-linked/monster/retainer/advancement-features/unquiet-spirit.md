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
      name: Enervating Curse
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 corruption damage; the target has 3 levels of drain
            low: 6 corruption damage; the target has 1 level of drain
            mid: 10 corruption damage; the target has 2 levels of drain
      sections:
        - label: Effect
          text: The next creature to make a [strike](../../../rule/combat/strike.md) against the target gains 1 [surge](../../../rule/resource/surge.md) for each level of drain, which must be used on that [strike](../../../rule/combat/strike.md).
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 7
      name: Ectoplasm
      power_roll:
        formula: + highest characteristic
        tiers:
            high: A < STRONG [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: A < WEAK [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: A < AVERAGE [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 10
      name: Death Phase
      sections:
        - label: Effect
          text: If the target has P < STRONG, they are phased until the end of their next turn. A phased target gains the unquiet spirit's Corruptive Phasing trait and can [fly](../../../movement/fly.md). They are visible but can't affect or be affed by other creatures or objects. A willing creature not subject to the ability's [potency](../../../rule/character/potency.md) can choose to automatically be affected.
      target: One creature
      usage: Main action
file_basename: unquiet-spirit
file_dpath: monster/retainer/advancement-features
item_id: unquiet-spirit
item_name: Unquiet Spirit Advancement Features
name: Unquiet Spirit Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/unquiet-spirit
source: mcdm.monsters.v1
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🏹 **Enervating Curse (Encounter)**
>
> | **Magic, Ranged, Strike** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 corruption damage; the target has 1 level of drain
> - **12-16:** 10 corruption damage; the target has 2 levels of drain
> - **17+:** 14 corruption damage; the target has 3 levels of drain
>
> **Effect:** The next creature to make a [strike](../../../rule/combat/strike.md) against the target gains 1 [surge](../../../rule/resource/surge.md) for each level of drain, which must be used on that [strike](../../../rule/combat/strike.md).

> **Level 7 Retainer Advancement Ability**

> 🔳 **Ectoplasm (Encounter)**
>
> | **Area, Magic**        |               **Main action** |
> |------------------------|------------------------------:|
> | **📏 3 cube within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** A < WEAK [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** A < AVERAGE [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** A < STRONG [slowed](../../../condition/slowed.md) and [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)

> **Level 10 Retainer Advancement Ability**

> 🏹 **Death Phase (Encounter)**
>
> | **Magic, Ranged, Strike** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Ranged 5**           | **🎯 One creature** |
>
> **Effect:** If the target has P < STRONG, they are phased until the end of their next turn. A phased target gains the unquiet spirit's Corruptive Phasing trait and can [fly](../../../movement/fly.md). They are visible but can't affect or be affed by other creatures or objects. A willing creature not subject to the ability's [potency](../../../rule/character/potency.md) can choose to automatically be affected.
