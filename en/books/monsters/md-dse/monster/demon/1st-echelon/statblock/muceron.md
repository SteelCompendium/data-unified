---
agility: 2
ev: "5"
file_basename: muceron
file_dpath: monster/demon/1st-echelon/statblock
free_strike: 3
intuition: 0
item_id: muceron
item_name: Muceron
keywords:
    - Abyssal
    - Demon
level: 3
might: 2
name: Muceron
organization: Horde
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/muceron
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
weaknesses:
    - Holy 3
---

```ds-sb
agility: 2
ev: "5"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; pull 2
          tier2: 7 damage; pull 3
          tier3: 8 damage; pull 4
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Barbed Tongues
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 5
      effects:
        - effect: '**Effect:** The muceron pulls each target up to 5 squares.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Tongue Pull
      target: Three creatures or objects
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the muceron is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the muceron can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Abyssal
    - Demon
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/muceron
    source: mcdm.monsters.v1
might: 2
name: Muceron
organization: Horde
presence: 1
reason: 0
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "30"
type: statblock
weaknesses:
    - Holy 3
```
