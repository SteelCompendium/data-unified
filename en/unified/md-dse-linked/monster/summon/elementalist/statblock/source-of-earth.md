---
agility: 1
ev: '-'
file_basename: source-of-earth
file_dpath: monster/summon/elementalist/statblock
free_strike: 5
intuition: -5
item_id: source-of-earth
item_name: Source of Earth
keywords:
    - Elemental
level: 8
might: 3
movement: Burrow
name: Source of Earth
presence: -3
reason: -5
role: Brute
scc: mcdm.heroes.v1/monster.summon.elementalist.statblock/source-of-earth
size: "2"
source: mcdm.heroes.v1
speed: 6
stability: 5
stamina: "45"
type: statblock
---

```ds-sb
agility: 1
ev: '-'
features:
    - effects:
        - effect: '[Difficult terrain](../../../../movement/difficult-terrain.md) composed of earth and stone doesn''t cost the source extra movement.'
      feature_type: trait
      icon: ⭐️
      name: Earthwalk
      type: feature
    - effects:
        - effect: When the source burrows, they create a [size](../../../../rule/character/size.md) 2 tunnel.
      feature_type: trait
      icon: ⭐️
      name: Tunneler
      type: feature
    - effects:
        - effect: A creature that has the [Earth Accepts Me](../../../../feature/ability/elementalist/level-3/earth-accepts-me.md) ability can use it as a free action to meld into the source.
      feature_type: trait
      icon: ⭐️
      name: Earth Harness
      type: feature
    - distance: Melee 2 or ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage; [push](../../../../movement/forced-movement.md) 3
          tier2: 9 damage; [push](../../../../movement/forced-movement.md) 4
          tier3: 12 damage; [push](../../../../movement/forced-movement.md) 5
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Boulder Bash
      target: One creature or object
      type: feature
      usage: Signature
free_strike: 5
intuition: -5
keywords:
    - Elemental
level: 8
metadata:
    scc: mcdm.heroes.v1/monster.summon.elementalist.statblock/source-of-earth
    source: mcdm.heroes.v1
might: 3
movement: Burrow
name: Source of Earth
organization: ""
presence: -3
reason: -5
role: Brute
size: "2"
speed: 6
stability: 5
stamina: "45"
type: statblock
```
