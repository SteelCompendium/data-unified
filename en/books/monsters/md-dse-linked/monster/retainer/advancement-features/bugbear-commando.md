---
features:
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 6 damage; M < WEAK [grabbed](../../../condition/grabbed.md)
          tier2: 9 damage; M < AVERAGE [grabbed](../../../condition/grabbed.md)
          tier3: 13 damage; M < STRONG [grabbed](../../../condition/grabbed.md)
        - effect: While the target is [grabbed](../../../condition/grabbed.md) this way, they can't communicate and all creatures and objects have concealment from them.
          name: Effect
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Face Grab
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 13 damage; M < STRONG [grabbed](../../../condition/grabbed.md)
            low: 6 damage; M < WEAK [grabbed](../../../condition/grabbed.md)
            mid: 9 damage; M < AVERAGE [grabbed](../../../condition/grabbed.md)
      sections:
        - label: Effect
          text: While the target is [grabbed](../../../condition/grabbed.md) this way, they can't communicate and all creatures and objects have concealment from them.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: Pull 8
          tier2: Pull 10
          tier3: Pull 12
        - effect: The target takes 1 damage for each square they are [pulled](../../../movement/forced-movement.md).
          name: Effect
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 7
      name: Shadow Drag
      power_roll:
        formula: + highest characteristic
        tiers:
            high: Pull 12
            low: Pull 8
            mid: Pull 10
      sections:
        - label: Effect
          text: The target takes 1 damage for each square they are [pulled](../../../movement/forced-movement.md).
      target: One creature or object
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 12 damage
          tier2: 18 damage
          tier3: 24 damage
        - effect: The target takes 15 damage, they are no longer [grabbed](../../../condition/grabbed.md), and they fall [prone](../../../condition/prone.md).
          name: Effect
      icon: "\U0001F5E1"
      keywords:
        - Melee
      level: 10
      name: Neck Snap
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 24 damage
            low: 12 damage
            mid: 18 damage
      sections:
        - label: Effect
          text: The target takes 15 damage, they are no longer [grabbed](../../../condition/grabbed.md), and they fall [prone](../../../condition/prone.md).
      target: One creature grabbed by the commando
      usage: Main action
file_basename: bugbear-commando
file_dpath: monster/retainer/advancement-features
item_id: bugbear-commando
item_name: Bugbear Commando Advancement Features
name: Bugbear Commando Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/bugbear-commando
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 6 damage; M < WEAK [grabbed](../../../condition/grabbed.md)
          tier2: 9 damage; M < AVERAGE [grabbed](../../../condition/grabbed.md)
          tier3: 13 damage; M < STRONG [grabbed](../../../condition/grabbed.md)
        - effect: While the target is [grabbed](../../../condition/grabbed.md) this way, they can't communicate and all creatures and objects have concealment from them.
          name: Effect
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Face Grab
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 13 damage; M < STRONG [grabbed](../../../condition/grabbed.md)
            low: 6 damage; M < WEAK [grabbed](../../../condition/grabbed.md)
            mid: 9 damage; M < AVERAGE [grabbed](../../../condition/grabbed.md)
      sections:
        - label: Effect
          text: While the target is [grabbed](../../../condition/grabbed.md) this way, they can't communicate and all creatures and objects have concealment from them.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: Pull 8
          tier2: Pull 10
          tier3: Pull 12
        - effect: The target takes 1 damage for each square they are [pulled](../../../movement/forced-movement.md).
          name: Effect
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 7
      name: Shadow Drag
      power_roll:
        formula: + highest characteristic
        tiers:
            high: Pull 12
            low: Pull 8
            mid: Pull 10
      sections:
        - label: Effect
          text: The target takes 1 damage for each square they are [pulled](../../../movement/forced-movement.md).
      target: One creature or object
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 12 damage
          tier2: 18 damage
          tier3: 24 damage
        - effect: The target takes 15 damage, they are no longer [grabbed](../../../condition/grabbed.md), and they fall [prone](../../../condition/prone.md).
          name: Effect
      icon: "\U0001F5E1"
      keywords:
        - Melee
      level: 10
      name: Neck Snap
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 24 damage
            low: 12 damage
            mid: 18 damage
      sections:
        - label: Effect
          text: The target takes 15 damage, they are no longer [grabbed](../../../condition/grabbed.md), and they fall [prone](../../../condition/prone.md).
      target: One creature grabbed by the commando
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/bugbear-commando
    source: mcdm.monsters.v1
name: Bugbear Commando Advancement Features
type: featureblock
```
