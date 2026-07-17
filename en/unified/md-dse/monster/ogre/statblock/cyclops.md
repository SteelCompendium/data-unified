---
agility: -1
ev: 12 for four minions
file_basename: cyclops
file_dpath: monster/ogre/statblock
free_strike: 4
intuition: 3
item_id: cyclops
item_name: Cyclops
keywords:
    - Giant
    - Ogre
level: 10
might: 5
name: Cyclops
organization: Minion
presence: -1
reason: -1
role: Controller
scc: mcdm.monsters.v1/monster.ogre.statblock/cyclops
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 5
stamina: "14"
type: statblock
with_captain: +4 bonus to speed
---

```ds-sb
agility: -1
ev: 12 for four minions
features:
    - ability_type: Signature Ability
      distance: 1 burst
      effects:
        - roll: Power Roll + 5
          tier1: 3 damage; A < 3 3 damage
          tier2: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; A < 4 4 damage
          tier3: 7 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone); A < 5 5 damage and [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Wild Slam
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The cyclops has line of effect only within 3 squares. Whenever the cyclops takes damage from a ranged ability, they can move up to 3 squares toward the source of the damage.
      feature_type: trait
      icon: ⭐️
      name: Limited Vision
      type: feature
free_strike: 4
intuition: 3
keywords:
    - Giant
    - Ogre
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.ogre.statblock/cyclops
    source: mcdm.monsters.v1
might: 5
name: Cyclops
organization: Minion
presence: -1
reason: -1
role: Controller
size: "3"
speed: 6
stability: 5
stamina: "14"
type: statblock
with_captain: +4 bonus to speed
```
