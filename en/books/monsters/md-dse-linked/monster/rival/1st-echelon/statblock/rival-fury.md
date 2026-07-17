---
agility: 1
ev: "16"
file_basename: rival-fury
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 0
item_id: rival-fury
item_name: Rival Fury
keywords:
    - Humanoid
    - Rival
level: 2
might: 2
name: Rival Fury
organization: Elite
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-fury
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "100"
type: statblock
---

```ds-sb
agility: 1
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [push](../../../../movement/forced-movement.md) 1
          tier2: 11 damage; [push](../../../../movement/forced-movement.md) 2
          tier3: 14 damage; [push](../../../../movement/forced-movement.md) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Brutal Impact
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 8 damage; M < 0 [grabbed](../../../../condition/grabbed.md)
          tier2: 13 damage; M < 1 [grabbed](../../../../condition/grabbed.md)
          tier3: 16 damage; M < 2 [grabbed](../../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Let's Tussle
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: Once per turn, when the fury [force moves](../../../../movement/forced-movement.md) a creature or object, or [shifts](../../../../movement/shifting.md) [adjacent](../../../../rule/combat/adjacent.md) to a creature or object, they can make a [free strike](../../../../feature/common/main-actions/free-strike.md) against that creature or object.
      feature_type: trait
      icon: ⭐️
      name: Overwhelm
      type: feature
    - effects:
        - effect: At the start of an encounter, the fury chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the fury and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-fury
    source: mcdm.monsters.v1
might: 2
name: Rival Fury
organization: Elite
presence: 0
reason: 0
role: Brute
size: 1M
speed: 5
stability: 3
stamina: "100"
type: statblock
```
