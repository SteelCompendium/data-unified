---
features:
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 4
      name: Winter's Breath
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 8 cold damage; [push](../../../movement/forced-movement.md) 5
            low: 3 cold damage; [push](../../../movement/forced-movement.md) 2
            mid: 5 cold damage; [push](../../../movement/forced-movement.md) 3
      sections:
        - label: Effect
          text: The weatherwise can [teleport](../../../movement/teleport.md) up to 5 squares before or after using this ability.
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 3 burst
      icon: ❇️
      keywords:
        - Area
        - Magic
      level: 7
      name: Spring's Rebirth
      sections:
        - label: Effect
          text: Each target can spend a [Recovery](../../../rule/health/recoveries.md), and can choose one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). That effect instead ends at the end of their turn.
      target: Each ally in the area
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 10
      name: Autumn's Decay
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 corruption damage; P < STRONG [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends)
            low: 6 corruption damage; P < WEAK [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends)
            mid: 10 corruption damage; P < AVERAGE [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
file_basename: high-elf-weatherwise
file_dpath: monster/retainer/advancement-features
item_id: high-elf-weatherwise
item_name: High Elf Weatherwise Advancement Features
name: High Elf Weatherwise Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/high-elf-weatherwise
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 4
      name: Winter's Breath
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 8 cold damage; [push](../../../movement/forced-movement.md) 5
            low: 3 cold damage; [push](../../../movement/forced-movement.md) 2
            mid: 5 cold damage; [push](../../../movement/forced-movement.md) 3
      sections:
        - label: Effect
          text: The weatherwise can [teleport](../../../movement/teleport.md) up to 5 squares before or after using this ability.
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 3 burst
      icon: ❇️
      keywords:
        - Area
        - Magic
      level: 7
      name: Spring's Rebirth
      sections:
        - label: Effect
          text: Each target can spend a [Recovery](../../../rule/health/recoveries.md), and can choose one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). That effect instead ends at the end of their turn.
      target: Each ally in the area
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 10
      name: Autumn's Decay
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 corruption damage; P < STRONG [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends)
            low: 6 corruption damage; P < WEAK [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends)
            mid: 10 corruption damage; P < AVERAGE [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/high-elf-weatherwise
    source: mcdm.monsters.v1
name: High Elf Weatherwise Advancement Features
type: featureblock
```
