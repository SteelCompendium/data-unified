---
agility: 2
ev: "12"
file_basename: animal
file_dpath: monster/animal/statblock
free_strike: 4
intuition: 1
item_id: animal
item_name: Animal
keywords:
    - Animal
level: 1
might: 0
name: Animal
organization: Elite
presence: -2
reason: -2
role: Harrier
scc: mcdm.monsters.v1/monster.animal.statblock/animal
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "60"
type: statblock
---

```ds-sb
agility: 2
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 9 damage
          tier3: 12 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Natural Weapon
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The animal moves up to their speed.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Rush
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: While outdoors or in a natural environment, the animal can negate a bane on their abilities or turn a double bane into a bane.
      feature_type: trait
      icon: ⭐️
      name: Nature's Spirit
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Animal
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.animal.statblock/animal
    source: mcdm.monsters.v1
might: 0
name: Animal
organization: Elite
presence: -2
reason: -2
role: Harrier
size: 1M
speed: 6
stability: 0
stamina: "60"
type: statblock
```
