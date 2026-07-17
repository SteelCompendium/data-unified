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
          text: The guide [shifts](../../../movement/shifting.md) up to their speed before and after the [strike](../../../rule/combat/strike.md).
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
            high: 16 damage; the guide and their mentor can each move up to their speed, then attempt to [hide](../../../feature/common/maneuvers/hide.md)
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
      level: 10
      name: Poison Blade
      sections:
        - label: Effect
          text: The guide applies poison to their weapon. The next time the guide obtains a tier 2 or tier 3 outcome on a weapon [strike](../../../rule/combat/strike.md), the [strike](../../../rule/combat/strike.md) deals an extra 10 poison damage, and if the target has M < AVERAGE, they are [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends). If the guide is [adjacent](../../../rule/combat/adjacent.md) to their mentor when they use Poison Blade, they apply poison to the mentor's weapon in the same way.
      target: Special
      usage: Main action
file_basename: goblin-guide
file_dpath: monster/retainer/advancement-features
item_id: goblin-guide
item_name: Goblin Guide Advancement Features
name: Goblin Guide Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/goblin-guide
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
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
          text: The guide [shifts](../../../movement/shifting.md) up to their speed before and after the [strike](../../../rule/combat/strike.md).
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
            high: 16 damage; the guide and their mentor can each move up to their speed, then attempt to [hide](../../../feature/common/maneuvers/hide.md)
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
      level: 10
      name: Poison Blade
      sections:
        - label: Effect
          text: The guide applies poison to their weapon. The next time the guide obtains a tier 2 or tier 3 outcome on a weapon [strike](../../../rule/combat/strike.md), the [strike](../../../rule/combat/strike.md) deals an extra 10 poison damage, and if the target has M < AVERAGE, they are [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends). If the guide is [adjacent](../../../rule/combat/adjacent.md) to their mentor when they use Poison Blade, they apply poison to the mentor's weapon in the same way.
      target: Special
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/goblin-guide
    source: mcdm.monsters.v1
name: Goblin Guide Advancement Features
type: featureblock
```
