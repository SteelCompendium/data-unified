---
agility: 1
ev: "16"
file_basename: big-animal-b
file_dpath: monster/animal/statblock
free_strike: 5
intuition: 1
item_id: big-animal-b
item_name: Big Animal B
keywords:
    - Animal
level: 2
might: 2
name: Big Animal B
organization: Elite
presence: 0
reason: -1
role: Mount
scc: mcdm.monsters.v1/monster.animal.statblock/big-animal-b
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: "80"
type: statblock
---

```ds-sb
agility: 1
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 10 damage; push 1
          tier3: 13 damage; push 2
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
        - effect: '**Effect:** The animal moves up to their speed. They can make a free strike against each creature who makes an opportunity attack against them during this movement.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Trundle
      target: Self
      type: feature
      usage: Maneuver
    - distance: Ranged 20
      effects:
        - effect: |-
            **Trigger:** The target is knocked prone.
            **Effect:** The animal moves up to their speed. If they end their turn adjacent to the target, they can use the [Stand Up](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/stand-up) maneuver to let the target stand, then get on to ride them.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Animal Rally
      target: One ally
      type: feature
      usage: Triggered action
    - effects:
        - effect: While riding the animal, two size 1 allies can occupy the same space.
      feature_type: trait
      icon: ⭐️
      name: Beast of Burden
      type: feature
    - effects:
        - effect: While outdoors or in a natural environment, the animal can negate a bane on their abilities or turn a double bane into a bane.
      feature_type: trait
      icon: ⭐️
      name: Nature's Spirit
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Animal
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.animal.statblock/big-animal-b
    source: mcdm.monsters.v1
might: 2
name: Big Animal B
organization: Elite
presence: 0
reason: -1
role: Mount
size: "3"
speed: 6
stability: 3
stamina: "80"
type: statblock
```
