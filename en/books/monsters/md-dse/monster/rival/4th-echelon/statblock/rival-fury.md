---
agility: 4
ev: "48"
file_basename: rival-fury
file_dpath: monster/rival/4th-echelon/statblock
free_strike: 10
intuition: 2
item_id: rival-fury
item_name: Rival Fury
keywords:
    - Humanoid
    - Rival
level: 10
might: 5
name: Rival Fury
organization: Elite
presence: 3
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-fury
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "260"
type: statblock
---

```ds-sb
agility: 4
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
          tier2: 21 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 25 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Seismic Crush
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 4 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage; M < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
          tier2: 21 damage; M < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
          tier3: 25 damage; M < 5 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Death Grip
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: Once per turn, when the fury [force moves](scc.v1:mcdm.heroes.v1/movement/forced-movement) a creature or object, or [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a creature or object, they can use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against that creature or object that has a double edge.
      feature_type: trait
      icon: ⭐️
      name: Devastate
      type: feature
    - effects:
        - effect: At the start of an encounter, the fury chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the fury and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 10
intuition: 2
keywords:
    - Humanoid
    - Rival
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-fury
    source: mcdm.monsters.v1
might: 5
name: Rival Fury
organization: Elite
presence: 3
reason: 0
role: Brute
size: 1M
speed: 5
stability: 3
stamina: "260"
type: statblock
```
