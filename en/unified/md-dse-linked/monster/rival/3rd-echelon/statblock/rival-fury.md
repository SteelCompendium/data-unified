---
agility: 3
ev: "40"
file_basename: rival-fury
file_dpath: monster/rival/3rd-echelon/statblock
free_strike: 9
intuition: 1
item_id: rival-fury
item_name: Rival Fury
keywords:
    - Humanoid
    - Rival
level: 8
might: 4
name: Rival Fury
organization: Elite
presence: 2
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-fury
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "220"
type: statblock
---

```ds-sb
agility: 3
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 13 damage; [push](../../../../movement/forced-movement.md) 3
          tier2: 18 damage; [push](../../../../movement/forced-movement.md) 4
          tier3: 22 damage; [push](../../../../movement/forced-movement.md) 5
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Bonebreaker
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 15 damage; M < 3 [grabbed](../../../../condition/grabbed.md)
          tier2: 21 damage; M < 4 [grabbed](../../../../condition/grabbed.md)
          tier3: 26 damage; M < 5 [grabbed](../../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Steelfist
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: Once per turn, when the fury [force moves](../../../../movement/forced-movement.md) a creature or object, or [shifts](../../../../movement/shifting.md) [adjacent](../../../../rule/combat/adjacent.md) to a creature or object, they can use a [signature ability](../../../../rule/combat/signature-ability.md) that gains an edge against that creature or object.
      feature_type: trait
      icon: ⭐️
      name: Rout
      type: feature
    - effects:
        - effect: At the start of an encounter, the fury chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the fury and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 9
intuition: 1
keywords:
    - Humanoid
    - Rival
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-fury
    source: mcdm.monsters.v1
might: 4
name: Rival Fury
organization: Elite
presence: 2
reason: 0
role: Brute
size: 1M
speed: 5
stability: 3
stamina: "220"
type: statblock
```
