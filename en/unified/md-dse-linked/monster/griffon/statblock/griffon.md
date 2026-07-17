---
agility: 2
ev: "16"
file_basename: griffon
file_dpath: monster/griffon/statblock
free_strike: 5
intuition: 1
item_id: griffon
item_name: Griffon
keywords:
    - Beast
    - Griffon
level: 2
might: 2
movement: Fly
name: Griffon
organization: Elite
presence: 2
reason: -1
role: Mount
scc: mcdm.monsters.v1/monster.griffon.statblock/griffon
size: "2"
source: mcdm.monsters.v1
speed: 9
stability: 2
stamina: "80"
type: statblock
---

```ds-sb
agility: 2
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; the griffon can [shift](../../../movement/shifting.md) 1 square
          tier2: 10 damage; the griffon [shifts](../../../movement/shifting.md) up to 2 squares
          tier3: 13 damage; the griffon [shifts](../../../movement/shifting.md) up to 3 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Claw Swipes
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 3 cube within 8
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage
          tier2: 6 damage; A < 1 [push](../../../movement/forced-movement.md) 3
          tier3: 9 damage; A < 2 [push](../../../movement/forced-movement.md) 4; [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
      name: Crack the Earth
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - cost: 3 Malice
      distance: 4 x 2 line within 1
      effects:
        - roll: Power Roll + 2
          tier1: '[Push](../../../movement/forced-movement.md) 3; A < 0 the [forced movement](../../../movement/forced-movement.md) is vertical'
          tier2: '[Push](../../../movement/forced-movement.md) 4; A < 1 the [forced movement](../../../movement/forced-movement.md) is vertical'
          tier3: '[Push](../../../movement/forced-movement.md) 5; A < 2 the [forced movement](../../../movement/forced-movement.md) is vertical'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Wing Buffet
      target: Each creature or object in the area
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The griffon takes damage.
            **Effect:** The griffon halves the damage, ignores any nondamaging effects associated with it, and [shifts](../../../movement/shifting.md) up to 2 squares.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Zephyr Feint
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: While [grabbed](../../../condition/grabbed.md) by the griffon, a creature has a double bane on the Escape Grab maneuver.
      feature_type: trait
      icon: ⭐️
      name: Beast of Prey
      type: feature
    - effects:
        - effect: Any power roll that could knock the griffon or their rider [prone](../../../condition/prone.md) takes a bane.
      feature_type: trait
      icon: ⭐️
      name: Steady
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Beast
    - Griffon
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.griffon.statblock/griffon
    source: mcdm.monsters.v1
might: 2
movement: Fly
name: Griffon
organization: Elite
presence: 2
reason: -1
role: Mount
size: "2"
speed: 9
stability: 2
stamina: "80"
type: statblock
```
