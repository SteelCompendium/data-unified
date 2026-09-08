---
features:
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 5 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 9 damage; [push](../../../movement/forced-movement.md) 2
          tier3: 12 damage; [push](../../../movement/forced-movement.md) 4
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Tackle
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; [push](../../../movement/forced-movement.md) 4
            low: 5 damage; [push](../../../movement/forced-movement.md) 1
            mid: 9 damage; [push](../../../movement/forced-movement.md) 2
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 7 damage
          tier2: 10 damage
          tier3: 15 damage
        - effect: Before or after the strike, the retainer and their mentor can each [shift](../../../movement/shifting.md) up to their speed.
          name: Effect
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Meet You There
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 15 damage
            low: 7 damage
            mid: 10 damage
      sections:
        - label: Effect
          text: Before or after the strike, the retainer and their mentor can each [shift](../../../movement/shifting.md) up to their speed.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 11 damage; one target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
          tier2: 16 damage; one target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
          tier3: 21 damage; one target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
        - effect: The retainer [shifts](../../../movement/shifting.md) up to 2 squares, and can move a creature [grabbed](../../../condition/grabbed.md) using this ability with them.
          name: Effect
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Nab and Stab
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; one target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
            low: 11 damage; one target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
            mid: 16 damage; one target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
      sections:
        - label: Effect
          text: The retainer [shifts](../../../movement/shifting.md) up to 2 squares, and can move a creature [grabbed](../../../condition/grabbed.md) using this ability with them.
      target: Each creature in the area
      usage: Main action
file_basename: harrier
file_dpath: monster/retainer/role-advancement
item_id: harrier
item_name: Harrier Abilities
name: Harrier Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/harrier
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 5 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 9 damage; [push](../../../movement/forced-movement.md) 2
          tier3: 12 damage; [push](../../../movement/forced-movement.md) 4
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Tackle
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; [push](../../../movement/forced-movement.md) 4
            low: 5 damage; [push](../../../movement/forced-movement.md) 1
            mid: 9 damage; [push](../../../movement/forced-movement.md) 2
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 7 damage
          tier2: 10 damage
          tier3: 15 damage
        - effect: Before or after the strike, the retainer and their mentor can each [shift](../../../movement/shifting.md) up to their speed.
          name: Effect
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Meet You There
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 15 damage
            low: 7 damage
            mid: 10 damage
      sections:
        - label: Effect
          text: Before or after the strike, the retainer and their mentor can each [shift](../../../movement/shifting.md) up to their speed.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 11 damage; one target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
          tier2: 16 damage; one target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
          tier3: 21 damage; one target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
        - effect: The retainer [shifts](../../../movement/shifting.md) up to 2 squares, and can move a creature [grabbed](../../../condition/grabbed.md) using this ability with them.
          name: Effect
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Nab and Stab
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; one target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
            low: 11 damage; one target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
            mid: 16 damage; one target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
      sections:
        - label: Effect
          text: The retainer [shifts](../../../movement/shifting.md) up to 2 squares, and can move a creature [grabbed](../../../condition/grabbed.md) using this ability with them.
      target: Each creature in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.role-advancement/harrier
    source: mcdm.monsters.v1
name: Harrier Abilities
type: featureblock
```
