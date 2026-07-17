---
agility: 2
ev: "28"
file_basename: rival-fury
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 7
intuition: 0
item_id: rival-fury
item_name: Rival Fury
keywords:
    - Humanoid
    - Rival
level: 5
might: 3
name: Rival Fury
organization: Elite
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-fury
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "160"
type: statblock
---

```ds-sb
agility: 2
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 10 damage; [push](../../../../movement/forced-movement.md) 2
          tier2: 15 damage; [push](../../../../movement/forced-movement.md) 3
          tier3: 18 damage; [push](../../../../movement/forced-movement.md) 4
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Thunderous Slam
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 11 damage; M < 1 [grabbed](../../../../condition/grabbed.md)
          tier2: 16 damage; M < 2 [grabbed](../../../../condition/grabbed.md)
          tier3: 21 damage; M < 3 [grabbed](../../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Roughed Up
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: Once per turn, when the fury [force moves](../../../../movement/forced-movement.md) a creature or object, or [shifts](../../../../movement/shifting.md) [adjacent](../../../../rule/combat/adjacent.md) to a creature or object, they can use a [signature ability](../../../../rule/combat/signature-ability.md) against that creature or object.
      feature_type: trait
      icon: ⭐️
      name: Overpower
      type: feature
    - effects:
        - effect: At the start of an encounter, the fury chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the fury and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 7
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-fury
    source: mcdm.monsters.v1
might: 3
name: Rival Fury
organization: Elite
presence: 1
reason: 0
role: Brute
size: 1M
speed: 5
stability: 3
stamina: "160"
type: statblock
```
