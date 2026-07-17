---
agility: -2
ev: "44"
file_basename: servok-builder
file_dpath: monster/valok/statblock
free_strike: 10
intuition: -1
item_id: servok-builder
item_name: Servok Builder
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 9
might: 4
name: Servok Builder
organization: Elite
presence: -5
reason: -4
role: Brute
scc: mcdm.monsters.v1/monster.valok.statblock/servok-builder
size: "3"
source: mcdm.monsters.v1
speed: 5
stability: 8
stamina: "240"
type: statblock
---

```ds-sb
agility: -2
ev: "44"
features:
    - ability_type: Signature Ability
      distance: 3 cube within 5
      effects:
        - roll: ""
          tier1: 15 damage; [push](../../../movement/forced-movement.md) 5, [prone](../../../condition/prone.md)
          tier2: 12 damage; [push](../../../movement/forced-movement.md) 3
          tier3: 8 damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Wrecking Ball
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 16 damage
          tier2: 23 damage; [grabbed](../../../condition/grabbed.md)
          tier3: 28 damage; [grabbed](../../../condition/grabbed.md); M < 4 vertical [push](../../../movement/forced-movement.md) 5
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Construction Arm
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 6 x 3 line within 1
      effects:
        - roll: ""
          tier1: '[Restrained](../../../condition/restrained.md) (EoT)'
          tier2: '[Slowed](../../../condition/slowed.md) (EoT)'
          tier3: No effect
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Lay the Foundation
      target: Special
      type: feature
      usage: Main action
    - distance: 6 wall within 3
      effects:
        - effect: '**Effect:** The builder creates a concrete wall. They can also remove any unoccupied squares of wet concrete within 3 squares of them, creating two additional squares of wall for each square of concrete removed.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
      name: Build Wall
      target: Special
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: A < 2 [restrained](../../../condition/restrained.md) (save ends)
          tier2: A < 3 [restrained](../../../condition/restrained.md) (save ends)
          tier3: A < 4 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Sputter
      target: The triggering creature or object
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The builder ignores [difficult terrain](../../../movement/difficult-terrain.md), and their abilities deal an extra 15 damage to objects.
      feature_type: trait
      icon: ⭐️
      name: Servok Siege Machine
      type: feature
    - effects:
        - effect: The builder's shape can't be changed by any external effect.
      feature_type: trait
      icon: ⭐️
      name: Crafted to Perfection
      type: feature
    - effects:
        - effect: While the builder isn't [bleeding](../../../condition/bleeding.md), [weakened](../../../condition/weakened.md), or [winded](../../../rule/health/winded.md), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
      feature_type: trait
      icon: ⭐️
      name: Valiar Might
      type: feature
free_strike: 10
intuition: -1
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.valok.statblock/servok-builder
    source: mcdm.monsters.v1
might: 4
name: Servok Builder
organization: Elite
presence: -5
reason: -4
role: Brute
size: "3"
speed: 5
stability: 8
stamina: "240"
type: statblock
```
