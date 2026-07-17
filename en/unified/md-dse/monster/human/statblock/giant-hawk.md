---
agility: 2
ev: "6"
file_basename: giant-hawk
file_dpath: monster/human/statblock
free_strike: 3
intuition: 1
item_id: giant-hawk
item_name: Giant Hawk
keywords:
    - Animal
    - Human
level: 1
might: 2
movement: Fly
name: Giant Hawk
organization: Platoon
presence: -2
reason: -3
role: Mount
scc: mcdm.monsters.v1/monster.human.statblock/giant-hawk
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage
          tier2: 7 damage
          tier3: 9 damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Talons
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The hawk moves up to their speed.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Dive
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: Once per turn when the hawk moves, any creature riding the hawk can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) during or after the movement.
      feature_type: trait
      icon: ⭐️
      name: Mounted Platform
      type: feature
free_strike: 3
intuition: 1
keywords:
    - Animal
    - Human
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/giant-hawk
    source: mcdm.monsters.v1
might: 2
movement: Fly
name: Giant Hawk
organization: Platoon
presence: -2
reason: -3
role: Mount
size: "2"
speed: 5
stability: 0
stamina: "30"
type: statblock
```
