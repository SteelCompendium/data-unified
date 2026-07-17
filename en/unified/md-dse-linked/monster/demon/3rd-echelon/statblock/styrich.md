---
agility: 4
ev: "10"
file_basename: styrich
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 3
intuition: 2
item_id: styrich
item_name: Styrich
keywords:
    - Abyssal
    - Demon
level: 8
might: 2
name: Styrich
organization: Horde
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/styrich
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 1
stamina: "45"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 4
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 4
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage; pull 1
          tier2: 10 damage; pull 2, [grabbed](../../../../condition/grabbed.md)
          tier3: 12 damage; pull 3, [grabbed](../../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Hair Whip
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 4 burst
      effects:
        - roll: Power Roll + 4
          tier1: A < 2 [slowed](../../../../condition/slowed.md) (save ends)
          tier2: '[Slowed](../../../../condition/slowed.md) (EoT) or A < 3 3 damage and [restrained](../../../../condition/restrained.md) (EoT)'
          tier3: '[Restrained](../../../../condition/restrained.md) (EoT) or A < 4 3 damage and [restrained](../../../../condition/restrained.md) (save ends)'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Tangled Nest
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the styrich is [winded](../../../../rule/health/winded.md), they gain an [edge](../../../../rule/dice/edge.md) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the styrich can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Abyssal
    - Demon
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/styrich
    source: mcdm.monsters.v1
might: 2
name: Styrich
organization: Horde
presence: 0
reason: 0
role: Hexer
size: 1L
speed: 6
stability: 1
stamina: "45"
type: statblock
weaknesses:
    - Holy 5
```
