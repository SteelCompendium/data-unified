---
features:
    - cost: Encounter
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 4 damage; [push](../../../movement/forced-movement.md) 2
          tier2: 6 damage; [push](../../../movement/forced-movement.md) 3
          tier3: 10 damage; [push](../../../movement/forced-movement.md) 5
        - effect: 'When the retainer uses this ability, they can choose for it to deal one of the following damage types: acid, cold, fire, lightning, poison, or sonic.'
          name: Effect
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      level: 4
      name: Elemental Blast
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 10 damage; [push](../../../movement/forced-movement.md) 5
            low: 4 damage; [push](../../../movement/forced-movement.md) 2
            mid: 6 damage; [push](../../../movement/forced-movement.md) 3
      sections:
        - label: Effect
          text: 'When the retainer uses this ability, they can choose for it to deal one of the following damage types: acid, cold, fire, lightning, poison, or sonic.'
      target: Each creature in the area
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 5 poison damage; M < WEAK [prone](../../../condition/prone.md)
          tier2: 8 poison damage; M < AVERAGE [prone](../../../condition/prone.md)
          tier3: 11 poison damage; M < STRONG [prone](../../../condition/prone.md)
        - effect: The area is [difficult terrain](../../../movement/difficult-terrain.md) for enemies. Any enemy has fire weakness 5 while in the area, and any enemy who ends their turn in the area and has no movement remaining falls [prone](../../../condition/prone.md).
          name: Effect
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      level: 7
      name: Oil Slick
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 11 poison damage; M < STRONG [prone](../../../condition/prone.md)
            low: 5 poison damage; M < WEAK [prone](../../../condition/prone.md)
            mid: 8 poison damage; M < AVERAGE [prone](../../../condition/prone.md)
      sections:
        - label: Effect
          text: The area is [difficult terrain](../../../movement/difficult-terrain.md) for enemies. Any enemy has fire weakness 5 while in the area, and any enemy who ends their turn in the area and has no movement remaining falls [prone](../../../condition/prone.md).
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      effects:
        - effect: The target must be size 1M or smaller.
          name: Special
          roll: Power Roll + highest characteristic
          tier1: 7 damage
          tier2: 11 damage
          tier3: 16 damage
        - effect: The area within 2 squares of the target is [difficult terrain](../../../movement/difficult-terrain.md), and each enemy in the area takes the same damage the object took.
          name: Effect
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Shattering Shards
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      sections:
        - label: Special
          text: The target must be size 1M or smaller.
        - label: Effect
          text: The area within 2 squares of the target is [difficult terrain](../../../movement/difficult-terrain.md), and each enemy in the area takes the same damage the object took.
      target: One Object
      usage: Main action
file_basename: controller
file_dpath: monster/retainer/role-advancement
item_id: controller
item_name: Controller Abilities
name: Controller Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/controller
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 4 damage; [push](../../../movement/forced-movement.md) 2
          tier2: 6 damage; [push](../../../movement/forced-movement.md) 3
          tier3: 10 damage; [push](../../../movement/forced-movement.md) 5
        - effect: 'When the retainer uses this ability, they can choose for it to deal one of the following damage types: acid, cold, fire, lightning, poison, or sonic.'
          name: Effect
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      level: 4
      name: Elemental Blast
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 10 damage; [push](../../../movement/forced-movement.md) 5
            low: 4 damage; [push](../../../movement/forced-movement.md) 2
            mid: 6 damage; [push](../../../movement/forced-movement.md) 3
      sections:
        - label: Effect
          text: 'When the retainer uses this ability, they can choose for it to deal one of the following damage types: acid, cold, fire, lightning, poison, or sonic.'
      target: Each creature in the area
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 5 poison damage; M < WEAK [prone](../../../condition/prone.md)
          tier2: 8 poison damage; M < AVERAGE [prone](../../../condition/prone.md)
          tier3: 11 poison damage; M < STRONG [prone](../../../condition/prone.md)
        - effect: The area is [difficult terrain](../../../movement/difficult-terrain.md) for enemies. Any enemy has fire weakness 5 while in the area, and any enemy who ends their turn in the area and has no movement remaining falls [prone](../../../condition/prone.md).
          name: Effect
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      level: 7
      name: Oil Slick
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 11 poison damage; M < STRONG [prone](../../../condition/prone.md)
            low: 5 poison damage; M < WEAK [prone](../../../condition/prone.md)
            mid: 8 poison damage; M < AVERAGE [prone](../../../condition/prone.md)
      sections:
        - label: Effect
          text: The area is [difficult terrain](../../../movement/difficult-terrain.md) for enemies. Any enemy has fire weakness 5 while in the area, and any enemy who ends their turn in the area and has no movement remaining falls [prone](../../../condition/prone.md).
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      effects:
        - effect: The target must be size 1M or smaller.
          name: Special
          roll: Power Roll + highest characteristic
          tier1: 7 damage
          tier2: 11 damage
          tier3: 16 damage
        - effect: The area within 2 squares of the target is [difficult terrain](../../../movement/difficult-terrain.md), and each enemy in the area takes the same damage the object took.
          name: Effect
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Shattering Shards
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      sections:
        - label: Special
          text: The target must be size 1M or smaller.
        - label: Effect
          text: The area within 2 squares of the target is [difficult terrain](../../../movement/difficult-terrain.md), and each enemy in the area takes the same damage the object took.
      target: One Object
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.role-advancement/controller
    source: mcdm.monsters.v1
name: Controller Abilities
type: featureblock
```
